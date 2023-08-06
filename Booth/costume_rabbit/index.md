---
title: ラビットスーツ
---

# ラビットスーツ

## 概要
本アセットは衣装の3Dモデルです。
※本データにアバター本体のデータは含まれておりません。

* lilToon ( https://lilxyzw.github.io/lilToon/#/ )を使用。
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* 衣装テクスチャファイル(psd, png)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 3.2.2
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.4.0
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.6.0

### 対応アバター
* [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.3
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.2.4

## 導入方法

### エルキュナ2ちゃん
1. lilToon, エルキュナ2ちゃん, Modular Avatarのパッケージを先にインポート。
2. rabbit.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エルキュナ2ちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/ERUQYUNA2/Prefab/ERUQYUNA2_素体Variant.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/rabbit/prefab/eruqyuna2_rabbit_MA.prefab`を配置。
5. アバターを調整
   * Body_torsoのBlendShapesの`Shrink_UpperLeg`,`Shrink_Knee`,`Shrink_LowerLeg`,`Shrink_Ankle`,`Shrink_Leg`を100に設定。
   * `Kemono_er`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### エミスティアちゃん
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. rabbit.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/rabbit/prefab/emistia_rabbit_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapeの`Knee_high`を100に設定。
   * `Kemono`,`Shoes`,`Tights`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2023/8/6 v1.0.0
販売開始

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】<br>
https://drive.google.com/file/d/1E-zZ0ymSvAJojmlWDb7oSGGN2_BUES2a/view?usp=sharing

【English】<br>
https://drive.google.com/file/d/1Y6XUru-h04hBG4YQV-G38OW9YstUT_iH/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/