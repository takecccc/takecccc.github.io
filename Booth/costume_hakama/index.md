---
title: ゆったり袴 
html:
   toc: true
---

# ゆったり袴

## 概要
本アセットは衣装の3Dモデルです。
※本データにアバター本体のデータは含まれておりません。

使用アセット
* lilToon ( https://lilxyzw.github.io/lilToon/#/ )
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* 衣装テクスチャファイル

## 動作確認環境
* Unity 2022.3.22f1
* VRCSDK 3.7.3
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.8.3
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.10.9

## 対応アバター
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.2
* [キュリシアちゃん](https://skymy.booth.pm/items/3990670) v1.1.2
* [リミリアちゃん](https://skymy.booth.pm/items/4365043) v1.0.8
* [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.6
* [ミコミアちゃん](https://skymy.booth.pm/items/5967855) v2.5
* [ネメシスちゃん](https://booth.pm/ja/items/5986971) v1.02
* [リオンちゃん](https://chloroterrace.booth.pm/items/6271911) v1.0
<!-- * [ユリスフィアちゃん](https://skymy.booth.pm/items/3486694) v1.4.1 -->
<!-- * [ルナールちゃん](https://booth.pm/ja/items/5319407) v1.18 -->
<!-- * [リリウムちゃん](https://booth.pm/ja/items/2745904) v1.02 -->
<!-- * [桔梗ちゃん](https://booth.pm/ja/items/3681787) v1.04 -->

## 導入方法

### 共通手順
1. lilToon, Modular Avatar, 各アバターのパッケージを先にインポート。
2. hakama.unitypackageをインポート。

### エミスティアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/PhysBone/EMISTIA_改変用Prefab_PhysBone.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_emistia_MA.prefab`を配置。
3. アバターを調整
   * `Shoes`,`Tights`を非表示にし、TagをEditorOnlyに変更。
   * `Kemono`のBlendShepesの`Tail_cover_off`を100に設定。
   * `Body`のBlendShepesの`elbow_off`,`UpperArm_off`,`Shoulder_off`,`Chest_off`を100に設定。
   * `Underwear`のBlendShepesの`Bra_off`を100に設定。

<!-- ### ユリスフィアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ユリスフィアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/YRISPHERE/Prefab/PhysBone/YRISPHERE_改変用素体_PhysBone.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_yrisphere_MA.prefab`を配置。
3. アバターを調整
   * `Kneehigh`と`Underwear`を非表示にし、TagをEditorOnlyに変更。
   * `Body`のBlendShapesの`Foot_Heel`と`Leg_off`を0に設定。
-->

### キュリシアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) キュリシアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/CURISHIA/Prefab/CURISHIA_改変用素体.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_curishia_MA.prefab`を配置。
3. アバターを調整
   * `Body`のBlendShapesの`Shrink_Shoulder`,`Shrink_UpperArm`,`Shrink_Elbow`,`Foot_flat`を100に設定。

### リミリアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リミリアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/LIMILIA/Prefab/LIMILIA_改変用Prefab.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_limilia_MA.prefab`を配置。
3. アバターを調整
   * `Boots`,`Tights`を非表示にし、TagをEditorOnlyに変更。
   * `Body`のBlendShapesの`Foot_flat`,`Shrink_Shoulder`,`Shrink_UpperArm`,`Shrink_Elbow`を100に設定。
   * `Underwear`のBlendShapesの`Bra_off`を100に設定。

### エルキュナ2ちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エルキュナ2ちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/ERUQYUNA2/Prefab/ERUQYUNA2_素体Variant.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_eruqyuna2_MA.prefab`を配置。
3. アバターを調整
   * `Body_torso`のBlendShapesの`Foot_flat`,`Shrink_Shoulder`,`Shrink_UpperArm`,`Shrink_Elbow`を100に設定。

### ミコミアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ミコミアちゃんの素体prefab<br>
   `Assets/SKYMY_Workshop/03_Avatar/MIKOMIA/Prefab/MIKOMIA_OriginalSotai2_kisekae`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_mikomia_MA.prefab`を配置。
3. アバターを調整
   * `Mi_Body_Torso`のBlend Shapeの`Foot flat`を75に設定。
   * `Mi_Body_Torso`のBlend Shapeの`Shrink_Shoulder`,`Shrink_UpperArm`,`Shrink_Elbow`を100に設定。
   * `Mi_Drawers`を非表示にし、TagをEditorOnlyに変更。

<!-- ### ルナールちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ルナールちゃんの素体prefab<br>
   `Assets/_Studio_7tsuki/7st01_Renard/着せ替え/7st01_Renard_Base Variant`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_renard_MA.prefab`を配置。
3. アバターを調整
   * `UnderWear`を非表示にし、TagをEditorOnlyに変更。
-->

<!-- ### リリウムちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リリウムちゃんの素体prefab<br>
   `Assets/Stray_Lamb/Lilium/Plefab/Lilium_Sotai_PB.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_lilium_MA.prefab`を配置。
3. アバターを調整
   * `Wear_Under`を非表示にし、TagをEditorOnlyに変更。
4. VRChat SDKのControlPanelからアップロード。
   * リリウムちゃんv1.02では、プレファブにDynamicBone Colliderが残っています。VRChat SDKのValidationsにてエラーが出ている場合は、Auto FixでPhysBone Colliderに置き換えてください。
   * ArmatureのHairに設定されているPhysBoneのCollidersの設定が抜けているので、Head(DynamicBornCollider)を設定してください。 -->

<!-- ### 桔梗ちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) 桔梗ちゃんの素体prefab<br>
   `Assets/Kikyo/Prefab/Kikyo_PB_kisekae.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_kikyo_MA.prefab`を配置。
3. アバターを調整
   * `Kikyo_Bra`,`Kikyo_GarterBelt`,`Kikyo_Shorts`を非表示にし、TagをEditorOnlyに変更。
-->

### ネメシスちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ネメシスちゃんの素体prefab<br>
   `Assets/Nemesis/Nemesis_Kisekae.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_nemesis_MA.prefab`を配置。
3. アバターを調整
   * `Costume_Inner`,`Costume_Pants`を非表示にし、TagをEditorOnlyに変更。

### リオンちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リオンちゃんの素体prefab<br>
   `Assets/Chloro † Terrace/RION_Ver1.0/Rion_ver1.0.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hakama/prefab/hakama_rion_MA.prefab`を配置。
3. アバターを調整
   * `Shoes`を非表示にし、TagをEditorOnlyに変更。

## 更新履歴
2024/11/23 v1.4.0
* PhysBoneの値を調整。
* ネメシスちゃんの対応を追加。
* リオンちゃんの対応を追加。

2024/11/15 v1.3.0
* ミコミアちゃんの対応を追加。
* テクスチャとマテリアルを更新

2024/11/11 v1.2.0
* エルキュナ2ちゃんとリミリアちゃんの対応を追加。
* メッシュとウェイトを調整。
* PhysBoneを調整。

2024/10/27 v1.1.0
* メッシュとウェイトを調整。
* 胸サイズと裾の長さのシェイプキーを追加。
* キュリシアちゃんの対応を追加。

2024/10/26 v1.0.0
* 販売開始。

## 利用規約 Terms of Use
本衣装はVN3ライセンスを利用した、Atelier Takec 一般衣装利用規約にて公開しております。
規約は下記のリンクをご確認ください。

【日本語】<br>
https://drive.google.com/file/d/1yaxYDm00SX59LCZe0Pcjyd5NOqdQ9wpi/view?usp=sharing

【English】<br>
https://drive.google.com/file/d/1eCaEGVWANymDMk5akvhpm-e5s2wCqiPO/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/