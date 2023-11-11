---
title: 【エミスティアちゃん対応】ショートパンツスタイル
html:
   toc: true
---

# 【エミスティアちゃん対応】ショートパンツスタイル

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した
衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* テクスチャを3パターン同梱。
* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* Modular Avatar ( https://github.com/bdunderscore/modular-avatar/releases )を使用。

## 内容物
- Unitypackageファイル
  - fbx
  - マテリアル
  - 着替えアニメーション、エクスプレッションメニュー
- テクスチャファイル(psd, png)
- モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRChar SDK 3.1.13
* エミスティアちゃん v1.2.4
* lilToon v1.3.7
* Modular Avatar 1.4.5

## 導入方法
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_short_pants.unitypackageをインポート。
3. 衣装を着せたい素体をHierarchyに配置。  
   ex) エミスティアちゃんの素体prefab。  
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. 衣装のプレファブをHierarchyに配置。
   `Assets/Takec/EMISTIA/model/short_pants/Prefabs/EMISTIA_short_pants_MA.prefab`
5. 結合データの調整
   1. `Shoes`,`Tights`を非表示とし、Tagを`EditorOnly`に変更。
   2. 素体の`Kemono`のBlendShapesでTail_cover_offを100に設定。
   3. 衣装のSkinned Mesh RendererのProbesのAnchor Overrideに素体のAnchor Overrideを指定
6. VRChat SDKのControlPanelからアップロード。

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1CpRzhaKJ8q9YsHD6LtxfRSaueQMVMf-Z/view?usp=sharing

【English】
https://drive.google.com/file/d/14wGBLg72iJ53NPmqdE3S7_xLAEe8plDn/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/