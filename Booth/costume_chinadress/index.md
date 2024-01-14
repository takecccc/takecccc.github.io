---
title: チャイナドレス
html:
   toc: true
---

# チャイナドレス

## 概要
本アセットは衣装の3Dモデルです。
※本データにアバター本体のデータは含まれておりません。

使用アセット
* lilToon ( https://lilxyzw.github.io/lilToon/#/ )
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )

対応アバター
* エルキュナ2ちゃん https://skymy.booth.pm/items/4926689
* リミリアちゃん https://skymy.booth.pm/items/4365043
* キュリシアちゃん https://skymy.booth.pm/items/3990670
* エミスティアちゃん https://skymy.booth.pm/items/2992265
* リセリエちゃん https://vividplum.booth.pm/items/4906263
<!-- * ユリスフィアちゃん https://skymy.booth.pm/items/3486694 -->

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* 衣装テクスチャファイル

## 動作確認環境
* Unity 2022.3.6f1
* VRCSDK 3.5.0
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.6.0
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.8.4

### 対応アバター
* [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.3
* [リミリアちゃん](https://skymy.booth.pm/items/4365043) v1.0.5
* [キュリシアちゃん](https://skymy.booth.pm/items/3990670) v1.1.1
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.1
* [リセリエちゃん](https://vividplum.booth.pm/items/4906263) v1.0.4
<!-- * [ユリスフィアちゃん](https://skymy.booth.pm/items/3486694) v1.3.0 -->

## 導入方法

### エルキュナ2ちゃん
1. lilToon, エルキュナ2ちゃん, Modular Avatarのパッケージを先にインポート。
2. chinadress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エルキュナ2ちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/ERUQYUNA2/Prefab/ERUQYUNA2_素体Variant.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/chinadress/prefab/eruqyuna2_chinadress_MA.prefab`を配置。
5. アバターを調整
   * `Armature/Hips/Hips.DB1`の`HipsDB1.L`と`HipsDB1.R`の`VRC Phys Bone`コンポーネントをオフに。
   * `Body_torso`のBlendShapesの`Foot_flat`を75に設定。
   * `Underwear_er`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### リミリアちゃん
1. lilToon, リミリアちゃん, Modular Avatarのパッケージを先にインポート。
2. chinadress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リミリアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/LIMILIA/Prefab/LIMILIA_改変用Prefab.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/chinadress/prefab/limilia_chinadress_MA.prefab`を配置。
5. アバターを調整
   * `Armature/Hips/Hips.DB1`の`HipsDB1.L`と`HipsDB1.R`の`VRC Phys Bone`コンポーネントをオフに。
   * `Body`のBlendShapesの`Foot_flat`を75に設定。
   * `Boots`,`Tights`,`Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### キュリシアちゃん
1. lilToon, キュリシアちゃん, Modular Avatarのパッケージを先にインポート。
2. chinadress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) キュリシアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/CURISHIA/Prefab/CURISHIA_改変用素体.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/chinadress/prefab/curishia_chinadress_MA.prefab`を配置。
5. アバターを調整
   * `Armature/Hips/Hips.DB1`の`HipsDB1.L`と`HipsDB1.R`の`VRC Phys Bone`コンポーネントをオフに。
   * `Body`のBlendShapeの`Foot_flat`を100に設定。
   * `Necklace`,`Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

<!-- ### ユリスフィアちゃん
1. lilToon, ユリスフィアちゃん, Modular Avatarのパッケージを先にインポート。
2. chinadress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ユリスフィアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/YRISPHERE/Prefab/PhysBone/YRISPHERE_改変用素体_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/chinadress/prefab/yrisphere_chinadress_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapesの`Foot_Heel`,`Leg_offf`を0に設定。
6. VRChat SDKのControlPanelからアップロード。 -->

### エミスティアちゃん
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. chinadress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/chinadress/prefab/emistia_chinadress_MA.prefab`を配置。
5. アバターを調整
   * `Kemono`のBlendShapeの`Tail_cover_off`を100に設定。
   * `Necklace`,`Shoes`,`Tights`,`Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### リセリエちゃん
1. lilToon, リセリエちゃん, Modular Avatarのパッケージを先にインポート。
2. chinadress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リセリエちゃんの素体prefab。<br>
   * `Assets\VIVIDPLUM\Liserie\Liserie_Naked.prefab`
   * `Assets\VIVIDPLUM\Liserie\Liserie_ShortHair_Naked.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/chinadress/prefab/liserie_chinadress_MA.prefab`を配置。
5. アバターを調整。
   * `Bra`,`Pants`を非表示にし、TagをEditorOnlyに変更。
   * `Body_torso`の次のBlendShapeを100に変更。<br>
     * `Hips1`, `Hips2`
     * `UpperLeg1.R`, `UpperLeg1.L`,
     * `UpperLeg2.R`, `UpperLeg2.L`,
     * `Unkle.R`, `Unkle.L`,
     * `Foot.R`, `Foot.L`,
     * `Toe.R`, `Toe.L`,
     * `Stocking.R`, `Stocking.L`,
   * `Body_torso`のBlendShapeについて、胸サイズを好みで調整。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/1/14 v1.2.0
* リセリエちゃんの対応を追加。
* 動作確認環境のバージョンを更新。

2023/11/12 v1.1.0
* 改変用にPSDファイルを追加

2023/11/11 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】<br>
https://drive.google.com/file/d/1p07pdEZKRLEHDRTsj6FhSVO0ZrSLYRVJ/view?usp=sharing

【English】<br>
https://drive.google.com/file/d/1MgB4Uw-tZI8E8fdbXYJaiqvgr_EhXw77/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/