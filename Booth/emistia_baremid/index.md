---
---
# 【エミスティアちゃん対応】ローライズデニム へそ出しスタイル

## 概要
本アセットはSKYMY Workshop様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* AvatarTools( https://takec.booth.pm/items/3411988 )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * 衣装結合済みprefab
  * マテリアル
  * 着替えアニメーション、エクスプレッションメニュー
* lilToon v1.3.6
* 衣装テクスチャファイル(clip, psd, png)
  ※psdはclipstudioで保存したものです。
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 2022.07.26.21.45
* エミスティアちゃん v1.2.3
* lilToon v1.3.6
* AvatarTools v2.2.3

## 導入方法
1. VRCSDK, lilToon, エミスティアちゃん, AvatarToolsのパッケージを先にインポート。
2. EMISTIA_baremid.unitypackageをインポート。
3. ベースとなるモデルをHierarchyに配置。
   ex) エミスティアちゃんの素体prefab。
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone`
4. 衣装prefabをHierarchyに配置。
   `Assets/Takec/EMISTIA/model/baremid/EMISTIA_baremid_prefab.prefab`
   `Assets/Takec/EMISTIA/model/baremid/EMISTIA_glove_prefab.prefab`
5. AvatarToolsで衣装を結合
   1. メニューからAvatarToolsのAvatarAssemblerを起動。
   2. AvatarAssemblerの`BaseObject`にHierarchyからベースモデルを指定。
   3. AvatarAssemblerの`CombineObjects`の`+`ボタンを押して枠を追加して、Hierarchyから衣装prefabを指定
   4. `Assemble!`ボタンを押すと結合したオブジェクトがHierarchyに配置されます。
6. 結合データの調整
   1. `Shoes`,`Tights`,`Underwear`は非表示にするか削除する必要があります。
   2. `Kemono`,`Necklace`はFXレイヤーで制御されます。
   3. 結合したモデルの衣装のSkinned Mesh RendererコンポーネントのAnchor Overrideに`Anchor Target`を指定します。
7. FX, ExMenu, ExParametersを`Assets/Takec/EMISTIA/model/baremid/ExMenu`に同梱したものに置き換え。
   1. `VRC Avatar Descriptor > Playable Layers > Base > FX`に`EMISTIA_FX_baremid`を設定。
   2. `VRC Avatar Descriptor > Expressions > Menu`に`EMISTIA_ExpMenu_baremid`を設定。
   3. `VRC Avatar Descriptor > Expressions > Parameters`に`EMISTIA_ExpParameters_baremid`を設定。
8. VRChat SDKのControlPanelからアップロード。

※アバターに結合済みのprefabも同梱していますが、将来のアップデートで使えなくなる可能性があります。ご了承ください。

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1YYXcIdsVgqMdor_94cQOGbz5hyEyLzjN/view?usp=sharing

【English】
https://drive.google.com/file/d/1m9cv1jfq2nr6FBCmLL8-pLnRTFMs7eXL/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/