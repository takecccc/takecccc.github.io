---
title: 【キュリシアちゃん対応】バスタオル
html:
   toc: true
---

# 【キュリシアちゃん対応】バスタオル

## 概要
本アセットはSKYMY Workshop様のキュリシアちゃん( https://skymy.booth.pm/items/3990670 )に対応した衣装の3Dモデルです。
※本データにキュリシアちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* AvatarTools( https://takec.booth.pm/items/3411988 )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * 衣装結合済みprefab
  * マテリアル
* lilToon v1.3.4
* 衣装テクスチャファイル(clip, psd, png)
  ※psdはclipstudioで保存したものです。
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 2022.07.26.21.45
* キュリシアちゃん 1.0.6
* lilToon v1.3.4
* AvatarTools v2.2.3

## 導入方法
1. VRCSDK, lilToon, キュリシアちゃん, AvatarToolsのパッケージを先にインポート。
2. curishia_towel.unitypackageをインポート。
3. ベースとなるモデルをHierarchyに配置。
   ex) キュリシアちゃんの素体prefab。
   `Assets/SKYMY_Workshop/03Avatar/CURISHIA/Prefab/CURISHIA改変用素体.prefab`
4. 衣装prefabをHierarchyに配置。
   `Assets/Takec/CURISHIA/towel/curishia_towel_prefab.prefab`
5. AvatarToolsで衣装を結合
   1. メニューからAvatarToolsのAvatarAssemblerを起動。
   2. AvatarAssemblerの`BaseObject`にHierarchyからベースモデルを指定。
   3. AvatarAssemblerの`CombineObjects`の`+`ボタンを押して枠を追加して、Hierarchyから衣装prefabを指定
   4. `Assemble!`ボタンを押すと結合したオブジェクトがHierarchyに配置されます。
6. 結合データの調整
   1. 下着は非表示にするか削除する必要があります。
   2. ヘッドバンド、ネックレスについては、Animatorで表示をコントロールしています。
7. FX, ExMenu, ExParametersを`Assets > Takec > CURISHIA > towel > ExMenu`に同梱したものに置き換え。
   1. `VRC Avatar Descriptor > Playable Layers > Base > FX`に`05_FX_cr_towel`を設定。
   2. `VRC Avatar Descriptor > Expressions > Menu`に`ExMenu_cr_towel`を設定。
   3. `VRC Avatar Descriptor > Expressions > Parameters`に`ExParameters_cr_towel`を設定。
8. VRChat SDKのControlPanelからアップロード。

※アバターに結合済みのprefabも同梱していますが、将来のアップデートで使えなくなる可能性があります。ご了承ください。

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1-3pkfNJhuMS6pD_ySeFrwIW5F6mI1VTp/view?usp=sharing

【English】
https://drive.google.com/file/d/1C71-8ppQAWMp9e734FojyTs80ouPRN6z/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/