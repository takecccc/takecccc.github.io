---
title: 【ソフィナ -Sophina- ちゃん対応】秋のボレロコーデ
---

# 【ソフィナ -Sophina- ちゃん対応】秋のボレロコーデ

## 概要
本アセットはLuku me様のソフィナちゃん( https://lukume.booth.pm/items/4044305 )に対応した衣装の3Dモデルです。
※本データにソフィナちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* AvatarTools( https://takec.booth.pm/items/3411988 )を使用。
* VRCAvatar3Tools( https://gatosyocora.booth.pm/items/2207020 )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * 衣装結合済みprefab
  * マテリアル
  * 衣装変更用追加FX,Menu,Parameters
* lilToon v1.3.6
* 衣装テクスチャファイル(clip, psd, png)
  ※psdはclipstudioで保存したものです。
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 2022.07.26.21.45
* ソフィナちゃん v1.1.2
* lilToon v1.3.6
* AvatarTools v2.2.3
* VRCAvatar3Tools v1.1.2

## 導入方法
### 結合済みprefabを用いる場合
1. VRCSDK, lilToon, ソフィナちゃん, VRCAvatar3Toolsのパッケージを先にインポート。
2. sophina_bolero.unitypackageをインポート。
3. メニューバー > VRCAvatar3Tools > AnimatorControllerCombinerを起動。
4. それぞれ次のように指定してCombine。

   SrcAnimatorController
   : `Assets > _LulkuMe > _Sophina > Animation > Controllers > 改変用 > SophinaFX 改変用 Hair,Face change.controller`

   DstAnimatorController
   : `Assets > Takec > Sophina > bolero > FX > SophinaFX_bolero.controller`

   <img src="img/2022-10-22-10-40-52.png">

5. 結合されたSophinaFX_boleroのレイヤー順が、追加衣装関連が上位になってしまっているため、一番下に来るように修正。
   <img src="img/2022-10-22-10-49-06.png">

6. メニューバー > VRCAvatar3Tools > ExpressionParametersCombinerを起動。

7. それぞれ次のように指定してCombine。

   SrcAnimatorController
   : `Assets > _LulkuMe > _Sophina > Animation > Expressions > 改変用 > Sophina_Parameter 改変用　Hair,Face change.asset`

   DstAnimatorController
   : `Assets > Takec > Sophina > bolero > FX > SophinaFX_Parameter_bolero.asset`

   <img src="img/2022-10-22-10-52-54.png">

8. `Assets > Takec > Sophina > bolero > Sophina_bolero_for_v1.1.2.prefab`をHierarchyに配置。

### 改変済みのアバターに着せる場合。
1. VRCSDK, lilToon, ソフィナちゃん, AvatarToolsのパッケージを先にインポート。
1. 着せたい対象(ベースモデル)をHierarchyに配置。
2. 衣装prefabをHierarchyに配置。
   `Assets > Takec > Sophina > bolero > sophina_bolero_prefab.prefab `
3. AvatarToolsで衣装を結合
   1. メニューバーからAvatarToolsのAvatarAssemblerを起動。
   2. AvatarAssemblerの`BaseObject`にHierarchyからベースモデルを指定。
   3. AvatarAssemblerの`CombineObjects`の`+`ボタンを押して枠を追加して、Hierarchyから衣装prefabを指定
   4. `Assemble!`ボタンを押すと結合したオブジェクトがHierarchyに配置されます。
4. 結合データの調整
   1. `Shoes`,`Socks`は非表示にするか削除する必要があります。
   2. `Body02`のシェイプキー「アンダー消し」を100にする必要があります。
   3. 結合した衣装のSkinnedMeshRendererのRoot BoneおよびAnchor Overrideに`AutoAnchorObject`を指定します。

※アバターに結合済みのprefabについては、将来のアップデートで使えなくなる可能性もございます。ご了承ください。

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】  
https://drive.google.com/file/d/1R37TvmohZ9G7--HkU3bAWqKetMtgJXLg/view?usp=sharing


【English】  
https://drive.google.com/file/d/1E-JUtvJ11f_POxfvCz5R41JR-iQE7AG8/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/