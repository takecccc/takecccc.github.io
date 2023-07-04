---
title: Light Shaft Projector
---

# Light Shaft Projector v2.0.0
## 目次
- [Light Shaft Projector v2.0.0](#light-shaft-projector-v200)
  - [目次](#目次)
  - [概要](#概要)
  - [動作確認環境](#動作確認環境)
  - [導入方法](#導入方法)
    - [1. 依存アセットのインポート](#1-依存アセットのインポート)
    - [2. LightShafrProjectorパッケージのインポート](#2-lightshafrprojectorパッケージのインポート)
    - [3. Prefabの設置](#3-prefabの設置)
      - [VideoPlayerへの対応が不要な場合](#videoplayerへの対応が不要な場合)
      - [iwaSync3のスクリーンとして用いる場合](#iwasync3のスクリーンとして用いる場合)
      - [Kinel式のスクリーンとして用いる場合](#kinel式のスクリーンとして用いる場合)
      - [AVPro Video Playerのスクリーンとして用いる場合(TopazChat Player等)](#avpro-video-playerのスクリーンとして用いる場合topazchat-player等)
    - [4. \_CameraDepthTextureの使用有無に対する設定](#4-_cameradepthtextureの使用有無に対する設定)
      - [\_CameraDepthTextureを使用する場合](#_cameradepthtextureを使用する場合)
      - [\_CameraDepthTextureを使用しない場合](#_cameradepthtextureを使用しない場合)
  - [その他の設定について](#その他の設定について)
    - [投影する画像・映像の変更方法](#投影する画像映像の変更方法)
    - [プロジェクターを複数設置する場合](#プロジェクターを複数設置する場合)
    - [FOV(Field Of View)を変更する場合](#fovfield-of-viewを変更する場合)
    - [Tilt補正](#tilt補正)
  - [トラブルシューティング](#トラブルシューティング)
    - [\_CameraDepthTextureを生成出来ているかチェックしたい。](#_cameradepthtextureを生成出来ているかチェックしたい)
  - [利用規約](#利用規約)
  - [更新履歴](#更新履歴)
    - [2023/7/4 v2.0.0](#202374-v200)
    - [2023/6/21 v1.2.0](#2023621-v120)
    - [2023/3/11 v.1.1.1](#2023311-v111)
    - [2022/11/27 v1.1.0](#20221127-v110)
    - [2022/11/24 v1.0.9](#20221124-v109)
    - [2022/8/13 v1.0.8](#2022813-v108)
    - [2022/8/12 v1.0.7](#2022812-v107)
    - [2022/6/4 v1.0.6](#202264-v106)
    - [2022/3/25 v1.0.5](#2022325-v105)
    - [2022/1/16 v1.0.4](#2022116-v104)
    - [2021/11/7 v1.0.3](#2021117-v103)
    - [2021/9/6 v1.0.2](#202196-v102)
    - [2021/9/3 v1.0.1](#202193-v101)
    - [2021/9/3 v1.0.0](#202193-v100)
  - [その他](#その他)

## 概要
本アセットはVRChatのワールド作成で利用することを想定した、
モデル・シェーダー・U#スクリプト を提供するものです。

サンプルワールド(v1.0.5)：
https://vrchat.com/home/world/wrld_845135e5-3e62-4f81-a9cb-4786cc5e3dfd

サンプルワールド(v2.0.0)：
https://vrchat.com/home/world/wrld_1843fa75-5d87-447d-a08c-87d630e7bec7

Unity2019対応。
iwaSync3, KineL式(りら式)VideoPlayer, AVPro Video Player(TopazChat Player等)のスクリーンとしても用いることができます。
* [iwaSync3](https://hoshinolabs.booth.pm/items/2666275)
* [KineL式 VideoPlayer](https://kinel.booth.pm/items/2758684)
* [TopazChat Player](https://tyounanmoti.booth.pm/items/1752066)

マテリアルによっては正常に描画されない場合もございます。ご注意ください。

## 動作確認環境
PCでのみ動作確認しています。
* Unity2019.4.31f1
* VRCSDK Base 3.2.1
* VRCSDK Worlds 3.2.1
* UdonSharp v1.1.8
* iwaSync3 v3.5.5
* Kinel式 v2.4.3_U_1.x
* TopazChat Player_3.3.1


## 導入方法
### 1. 依存アセットのインポート
iwaSync3またはKinel式のVideoPlayerのスクリーンとして使用する場合、先にUdonSharp(U#)とiwaSync3またはKinel式のインポートを実施してください。
どちらのスクリーンとしても用いない場合は、このステップはスキップしてください。

### 2. LightShafrProjectorパッケージのインポート
LightShaftProjector.unitypackageをインポートしてください。

この際、依存アセットが存在しないことによるエラーを防ぐため、
* iwaSync3のスクリーンとして用いない場合は `Assets/LightShaftProjector/for_iwaSync` フォルダのチェックを外してください。
* Kinel式のスクリーンとして用いない場合は `Assets/LightShaftProjector/for_Kinel` フォルダのチェックを外してください。

### 3. Prefabの設置
#### VideoPlayerへの対応が不要な場合
`Assets/LightShaftProjector/LightShaftProjector.prefab` をHierarchyに設置してください。

#### iwaSync3のスクリーンとして用いる場合
`Assets/LightShaftProjector/for_iwaSync/LightShaftProjector_iwaSyncScreen.prefab` をHierarchyに設置してください。

`LightShaftProjector_iwaSyncScreen > Projector > ProjectionGimmick > textureUpdate` にアタッチされているU#スクリプト(ProjectorVideoScreen_iwaSync)のCoreにiwaSync3のCoreを設定してください。

<img src="img/2023-06-29-22-12-01.png">

#### Kinel式のスクリーンとして用いる場合
`Assets/LightShaftProjector/for_Kinel/LightShaftProjector_KinelScreen.prefab` をHierarchyに設置してください。

`LightShaftProjector_iwaSyncScreen > Projector > ProjectionGimmick > textureUpdate` にアタッチされているU#スクリプト(ProjectorVideoScreen_Kinel)のVideo PlayerにKinelVideoPlayerのKineLVP Systemを設定してください。

<img src="img/2023-06-29-22-13-22.png">
    
#### AVPro Video Playerのスクリーンとして用いる場合(TopazChat Player等)
1. `Assets/LightShaftProjector/for_AVProVideoPlayer/LightShaftProjector_AVProVideoScreen.prefab` をHierarchyに設置してください。

2. `LightShaftProjector_AVProVIdeoScreen > Projector > ProjectionGimmik`内にある、`Projection > Projection`および`LightShaft > LightShaft`にアタッチされている`VRC AVPro Video Screen`のVideoPlayerに、`VRC AVPro Video Player`がアタッチされているオブジェクトを設定してください。

   <img src="img/2023-06-29-22-04-06.png">

3. `LightShaftProjector_AVProVIdeoScreen > Projector > ProjectionGimmik`内にある、`Projection > Projection`および`LightShaft > LightShaft`のマテリアルの`Is AVPro Video`にチェックを入れてください。<br>
   AVPro Videoモードの場合、テクスチャはガンマ補正されます。設定するテクスチャの設定のsRGBのチェックを外してください。

### 4. _CameraDepthTextureの使用有無に対する設定

#### _CameraDepthTextureを使用する場合
1. LightShaftマテリアルのUseCameraDepthにチェックを入れて下さい。
2. リファレンスカメラ(Main Camera)のDepthTextureModeを設定する必要があります。<br>
   VRC Scene DescriptorのReferece CameraにMain Cameraが設定されていることを確認してください。
3. Inspectorからはそのまま設定できないため、`Assets/LightShaftProjector/Scripts/DepthTextureMode.cs`をMain Cameraにアタッチし、ModeをDepthに変更してください。
   <img src="img/2023-06-29-22-17-09.png">

- ※_CameraDepthTextureはRealtimeなDirectionalLightが存在し、かつ影を受けるマテリアルでないと正常に動作しません。
- ※DirectionalLightのCulling Maskで対象としていないオブジェクトでも_CameraDepthTextureには反映されます。

#### _CameraDepthTextureを使用しない場合
LightShaftマテリアルを次のように設定する必要があります。
| Property | Value |
| --- | --- |
| UseCameraDepth | False |
| Cull | Off |
| ZTest | LessEqual |

前後関係を判断できず、一部の描写に制限がかかってしまいますが、
そこまで違和感なく表現できるかと思います。

## その他の設定について
### 投影する画像・映像の変更方法
ProjectionとLightShaftのマテリアルのTextureを指定してください。
(iwaSync3およびKinelとの連携については、U#からTextureの設定が行われます。)

### プロジェクターを複数設置する場合
プロジェクターからのDepthをRenderTextureを使用して取得しているため、マテリアルを分けた上でことなるRenderTextureを設定する必要があります。

### FOV(Field Of View)を変更する場合
Depthカメラ・Projector・マテリアル・LightShaftモデルの設定を合わせる必要があります。
FOV15°と30°のLightShaftモデルは用意してありますが、他のFOVが必要な場合は適宜用意をお願いいたします。

### Tilt補正
プロジェクターの投影面を回転させることにより、斜めから投影しても正しい形で投影することが可能です。
1. LightShaftProjectorのPrefabのルートを投影面に正対するように回転させる。
2. `ProjectionGimmick`を投影したい角度に調整
3. マテリアル `ProjectionWidthDepth`, `LightShaft`のScreen Tiltに、`ProjectionGimmick`のRotation値を入力。

## トラブルシューティング
### _CameraDepthTextureを生成出来ているかチェックしたい。
_CameraDepthTextureの内容を描画するシェーダーを作成しました。

`Assets/LightShaftProjector/Debug/CameraDepthTextureTestPlane.prefab`をHierarchyに配置してください。

プレーンを置く前
<img src="img/2023-03-11-21-04-58.png">

プレーンを置いた後
<img src="img/2023-03-11-21-03-49.png">

正常に_CameraDepthTextureが生成されていると、このように深度が表示されます。

## 利用規約
本データはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】<br>
https://drive.google.com/file/d/1fZ-5i4ItK_Tpkdhhth_YFttbmicsT8yC/view?usp=sharing

【English】<br>
https://drive.google.com/file/d/1AaNaz9FnGFHD2i7_KNv_PmkcEFN4dnSU/view?usp=sharing

## 更新履歴
### 2023/7/4 v2.0.0
* リファクタリング
* 影の描画品質を向上
* 処理負荷を軽減
* カメラと鏡に映るようにレイヤーを変更
* プロジェクターのモデルを更新
* テクスチャの設定を更新
* フォルダ構成を整理
* AVPro Video Screenとしての動作を確認

※互換性の無い更新が多く含まれます。<br>
**プロジェクトのバックアップを取った上で**、既存のLight Shaft Projectorのフォルダを削除してからインポートしてください。

### 2023/6/21 v1.2.0
* UdonSharp v1.1.8での動作を確認。
* iwaSync v3.5.5での動作を確認。
* Kinel Video Player v2.4.3_U_1.xに対応。

### 2023/3/11 v.1.1.1
* _CameraDepthTextureが生成されているか確認するシェーダーを追加。

### 2022/11/27 v1.1.0
* Kinel式 VideoPlayerのスクリーンとして使用するためのスクリプトを追加。

### 2022/11/24 v1.0.9
* idle画像を変更。
* iwaSync用のUdonスクリプトをVCCのU#1.0に移行。<br>
  VCCに移行していないプロジェクトではiwaSyncの画面として動作しなくなります。<br>
  VCCに移行する際はiwaSyncも更新が必要となりますのでご注意ください。

### 2022/8/13 v1.0.8
* Projectorの光が当たらない場所にProjectionされる場合があった不具合を修正。

### 2022/8/12 v1.0.7
* iwaSync3 U#1.0版に対応したpackageを追加。

### 2022/6/4 v1.0.6
* アスペクト比が異なるテクスチャを入力しても正しく表示するように変更。

### 2022/3/25 v1.0.5
* LightShaftの描画品質向上
* マテリアルのCull設定等をプロパティに追加。
* iwaSync3との連携コンポーネントを1つに集約

### 2022/1/16 v1.0.4
* iwaSyncでLiveを再生した際に上下反転していた不具合を修正。

### 2021/11/7 v1.0.3
* シェーダーをまとめてシンプルに(CameraDepthTextureで分けていたシェーダーはマテリアル設定で切り替えるように変更しました。)
* 最低限必要なデータに絞ってファイル構成をシンプルに

### 2021/9/6 v1.0.2
* 投影角度補正機能を追加。
* マテリアルのフォルダを整理。

### 2021/9/3 v1.0.1
* LightShaftの距離減衰の計算を修正。
* Boothで販売開始。

### 2021/9/3 v1.0.0
* 販売前テスト

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
