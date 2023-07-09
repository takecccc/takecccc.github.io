---
title: 【エミスティアちゃん対応】ウィッチスタイル3Dモデル
---

# 【エミスティアちゃん対応】ウィッチスタイル3Dモデル

## 概要
本アセットはSKYMY Workshop様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* Modular Avatar ( https://github.com/bdunderscore/modular-avatar/releases )を使用。
* Clothの頂点数によってVeryPoorとなります。

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
  * コンポーネント設定済み衣装prefab
* 衣装テクスチャファイル(psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 3.2.1
* [エミスティアちゃん v1.2.4](https://skymy.booth.pm/items/2992265)
* [lilToon v1.4.0](https://lilxyzw.github.io/lilToon/#/)
* [Modular Avatar 1.6.0](https://modular-avatar.nadena.dev/ja/)

## 導入方法
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_bikini.unitypackageをインポート。
3. 衣装を着せたい素体をHierarchyに配置。  
   ex) エミスティアちゃんの素体prefab。  
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone`
4. 衣装およびMagicWandのプレファブをHierarchyの素体直下に配置。
   * `Assets/Takec/EMISTIA/model/witch/prefab/EMISTIA_witch_MA.prefab`
   * `Assets/Takec/EMISTIA/model/witch/prefab/magic_wand_MA.prefab`
5. 素体データの調整
   1. `Shoes`,`Tights`を非表示に設定してTagをEditorOnlyに変更。
   2. `Kemono`のBlendShapesの`Tail_cover_off`を100に設定。
6. VRChat SDKのControlPanelからアップロード。

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1MYEyUG8i4yDnW1XpkjFKEh9BFKqZ6Le1/view?usp=sharing

【English】
https://drive.google.com/file/d/1Kq4lXTFnAUv1EH7kDBNRl0eeNsrFHmz3/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
