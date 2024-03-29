---
title: ラビットスーツ
html:
   toc: true
---

# ラビットスーツ

## 概要
本アセットは衣装の3Dモデルです。
※本データにアバター本体のデータは含まれておりません。

* lilToon ( https://lilxyzw.github.io/lilToon/#/ )を使用。
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )を使用。

対応アバター
* エルキュナ2ちゃん https://skymy.booth.pm/items/4926689
* エミスティアちゃん https://skymy.booth.pm/items/2992265
* キュリシアちゃん https://skymy.booth.pm/items/3990670
* リミリアちゃん https://skymy.booth.pm/items/4365043
* ユリスフィアちゃん https://skymy.booth.pm/items/3486694

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
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.7.0

### 対応アバター
* [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.3
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.2.4
* [キュリシアちゃん](https://skymy.booth.pm/items/3990670) v1.1.1
* [リミリアちゃん](https://skymy.booth.pm/items/4365043) v1.0.5
* [ユリスフィアちゃん](https://skymy.booth.pm/items/3486694) v1.3.0

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

### キュリシアちゃん
1. lilToon, キュリシアちゃん, Modular Avatarのパッケージを先にインポート。
2. rabbit.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) キュリシアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/CURISHIA/Prefab/CURISHIA_改変用素体.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/rabbit/prefab/curishia_rabbit_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapeの`Shrink_UpperLeg`,`Shrink_Knee`,`Shrink_LowerLeg`,`Shrink_Ankle`,`Shrink_Leg`,`Foot_flat`を100に設定。
   * `Kemono`,`Headbang`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### リミリアちゃん
1. lilToon, リミリアちゃん, Modular Avatarのパッケージを先にインポート。
2. rabbit.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リミリアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/LIMILIA/Prefab/LIMILIA_改変用Prefab.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/rabbit/prefab/eruqyuna2_rabbit_MA.prefab`を配置。(エルキュナ2ちゃんと共通素体)
5. アバターを調整
   * BodyのBlendShapesの`Shrink_UpperLeg`,`Shrink_Knee`,`Shrink_LowerLeg`,`Shrink_Ankle`,`Shrink_Leg`を100に設定。
   * `Kemono_er`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### ユリスフィアちゃん
1. lilToon, ユリスフィアちゃん, Modular Avatarのパッケージを先にインポート。
2. rabbit.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ユリスフィアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/YRISPHERE/Prefab/PhysBone/YRISPHERE_改変用素体_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/rabbit/prefab/yrisphere_rabbit_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapesの`Foot_Heel`,`Leg_offf`を0に設定。
   * BodyのBlendShapesの`UpperLeg_off`,`knee_off`を100に設定。
   * UnderwearのBlendShapesの`gather_off`を100に設定。
   * `kneehigh`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2023/8/8 v1.2.0
* ユリスフィアちゃんの対応を追加。

2023/8/6 v1.1.0
* メッシュ・ウェイトを微調整。
* キュリシアちゃんの対応を追加。

2023/8/6 v1.0.0
* 販売開始。

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