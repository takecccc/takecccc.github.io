---
title: 【エミスティアちゃん対応】パーティードレス
html:
   toc: true
---

# 【エミスティアちゃん対応】パーティードレス

## 概要
本アセットはSKYMY Workshop様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* lilToon ( https://lilxyzw.github.io/lilToon/#/ )を使用。
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* lilToon v1.4.0
* 衣装テクスチャファイル(psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 3.2.0
* [エミスティアちゃん v1.2.4](https://skymy.booth.pm/items/2992265)
* [lilToon v1.4.0](https://lilxyzw.github.io/lilToon/#/)
* [Modular Avatar 1.5.1](https://modular-avatar.nadena.dev/ja/)

## 導入方法
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_party_dress.unitypackageをインポート。
3. 衣装を着せたい素体をHierarchyに配置。  
   ex) エミスティアちゃんの素体prefab。  
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone`
4. 衣装のプレファブをHierarchyの素体直下に配置。
   `Assets/Takec/EMISTIA/model/party_dress/prefab/EMISTIA_party_dress_MA.prefab`
5. 素体データの調整
   1. `Hair`, `Hairpin`, `Ornaments`, `Kemono`, `Necklace`, `Shoes`, `Tights`を非表示に設定してTagをEditorOnlyに変更。
   2. `Body`のBlendShapesの`thigh_large`, `Foot_off`を100に設定。
   3. `Kemono`のBlendShapesの`Tail_cover_off`を100に設定。
   4. `Underwear`のBlendShapesの`Underwear_string_off`, `Underwear_race_off`, `Underwear_hirahira_off`, `thigh_large`を100に設定。
6. VRChat SDKのControlPanelからアップロード。

※改変用素体Prefabを元としたPrefab Variantも用意してあります。  
`Assets/Takec/EMISTIA/model/party_dress/prefab/EMISTIA_party_dress_MA.prefab`

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】  
https://drive.google.com/file/d/1eAYhzM6ugKkAbO0_OAqGH2Tx1psReJ6B/view?usp=sharing

【English】  
https://drive.google.com/file/d/1xuhduVn2esa0oiamRgGUvQtbnIytnS1O/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/