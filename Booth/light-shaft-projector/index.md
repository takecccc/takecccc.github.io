# Light Shaft Projector
## 概要
本アセットはVRChatのワールド作成で利用することを想定した、
モデル・シェーダー・U#スクリプト を提供するものです。

サンプルワールド：
https://vrchat.com/home/world/wrld_845135e5-3e62-4f81-a9cb-4786cc5e3dfd

Unity2019対応。
iwaSync3およびKineL式(りら式)VideoPlayerのスクリーンとしても用いることができます。
* iwaSync3 https://hoshinolabs.booth.pm/items/2666275
* KineL式 https://kinel.booth.pm/items/2758684

マテリアルによっては正常に描画されない場合もございます。ご注意ください。

## 動作確認環境
PCでのみ動作確認しています。
* Unity2019.4.31f1
* VRCSDK Base 3.1.10
* VRCSDK Worlds 3.1.10
* UdonSharp v1.1.5
* iwaSync3 v3.5.1
* Kinel式 v2.3.0(VCC向け U#1.x.x)


## 導入方法
1. 依存アセットのインポート
   iwaSync3またはKinel式のVideoPlayerのスクリーンとして使用する場合、先にUdonSharp(U#)とiwaSync3またはKinel式のインポートを実施してください。
   どちらのスクリーンとしても用いない場合は、このステップはスキップしてください。
2. LightShafrProjectorパッケージのインポート
   LightShaftProjector.unitypackageをインポートしてください。
3. 不要なデータの削除
   依存アセットが存在しないことによるエラーを解消するため、
   iwaSync3のスクリーンとして用いない場合は `Assets/LightShaftProjector/for_iwaSync` フォルダを、
   Kinel式のスクリーンとして用いない場合は `Assets/LightShaftProjector/for_Kinel` フォルダを
   削除してください。
4. Prefabの設置
   * VideoPlayerへの対応が不要な場合
     `Assets/LightShaftProjector/LightShaftProjector.prefab` をHierarchyに設置してください。
   * iwaSync3のスクリーンとして用いる場合
     `Assets/LightShaftProjector/for_iwaSync/LightShaftProjector_iwaSyncScreen.prefab` をHierarchyに設置してください。
     `LightShaftProjector_iwaSyncScreen > Projector > ProjectionGimmick > textureUpdate` にアタッチされているU#スクリプト(ProjectorVideoScreen_iwaSync)のCoreにiwaSync3のCoreを設定してください。
   * Kinel式のスクリーンとして用いる場合
     `Assets/LightShaftProjector/for_Kinel/LightShaftProjector_KinelScreen.prefab` をHierarchyに設置してください。
     `LightShaftProjector_iwaSyncScreen > Projector > ProjectionGimmick > textureUpdate` にアタッチされているU#スクリプト(ProjectorVideoScreen_Kinel)のVideo PlayerにKinelVideoPlayerのKineLVP Systemを設定してください。
5. _CameraDepthTextureの使用有無に対する設定
   * _CameraDepthTextureを使用する場合
     1. LightShaftマテリアルのUseCameraDepthにチェックを入れて下さい。
     2. リファレンスカメラ(Main Camera)のDepthTextureModeを設定する必要があります。
        Inspectorからはそのまま設定できないため、`Assets/LightShaftProjector/Scripts/DepthTextureMode.cs`をMain Cameraにアタッチし、ModeをDepthに変更してください。

     _CameraDepthTextureはRealtimeなDirectionalLightが存在し、かつ影を受けるマテリアルでないと正常に動作しません。
     ※DirectionalLightのCulling Maskで対象としていないオブジェクトでも_CameraDepthTextureには反映されます。

   * _CameraDepthTextureを使用しない場合
     LightShaftマテリアルのUseCameraDepthのチェックを外してください。
     前後関係を判断できず、一部の描写に制限がかかりますがあまり違和感なく表現できるかと思います。

## その他の設定について
### 投影する画像・映像の変更方法
ProjectionとLightShaftのマテリアルのTextureを指定してください。
(iwaSync3およびKinelとの連携については、U#からTextureの設定が行われます。)

### プロジェクターを複数設置する場合
プロジェクターからのDepthをRenderTextureを使用して取得しているため、マテリアルを分けた上でことなるRenderTextureを設定する必要があります。

### FOV(Field Of View)を変更する場合
Depthカメラ・Projector・マテリアル・LightShaftモデルの設定を合わせる必要があります。
FOV15°と30°のLightShaftモデルは用意してありますが、他のFOVが必要な場合は適宜用意をお願いいたします。

## 利用規約
本データはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1fZ-5i4ItK_Tpkdhhth_YFttbmicsT8yC/view?usp=sharing

【English】
https://drive.google.com/file/d/1AaNaz9FnGFHD2i7_KNv_PmkcEFN4dnSU/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
