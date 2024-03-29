---
title: バーテンダー
html:
   toc: true
---

# バーテンダー

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
<!-- * ユリスフィアちゃん https://skymy.booth.pm/items/3486694 -->
<!-- * エミスティアちゃん https://skymy.booth.pm/items/2992265 -->

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* 衣装テクスチャファイル(psd, png)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 3.3.0
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.4.1
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.7.5

### 対応アバター
* [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.3
* [リミリアちゃん](https://skymy.booth.pm/items/4365043) v1.0.5
* [キュリシアちゃん](https://skymy.booth.pm/items/3990670) v1.1.1
<!-- * [ユリスフィアちゃん](https://skymy.booth.pm/items/3486694) v1.3.0 -->
<!-- * [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.2.4 -->

## 導入方法

### エルキュナ2ちゃん
1. lilToon, エルキュナ2ちゃん, Modular Avatarのパッケージを先にインポート。
2. bartender.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エルキュナ2ちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/ERUQYUNA2/Prefab/ERUQYUNA2_素体Variant.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/bartender/prefab/eruqyuna2_bartender_MA.prefab`を配置。
5. アバターを調整
   * Body_torsoのBlendShapesの`Shrink_UpperLeg`,`Shrink_Knee`を100に設定。
   * Body_torsoのBlendShapesの`Foot_flat`を70に設定。
6. VRChat SDKのControlPanelからアップロード。

### リミリアちゃん
1. lilToon, リミリアちゃん, Modular Avatarのパッケージを先にインポート。
2. bartender.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リミリアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/LIMILIA/Prefab/LIMILIA_改変用Prefab.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/bartender/prefab/limilia_bartender_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapesの`Shrink_UpperLeg`,`Shrink_Knee`を100に設定。
   * BodyのBlendShapesの`Foot_flat`を70に設定。
   * `Boots`,`Tights`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### キュリシアちゃん
1. lilToon, キュリシアちゃん, Modular Avatarのパッケージを先にインポート。
2. bartender.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) キュリシアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/CURISHIA/Prefab/CURISHIA_改変用素体.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/bartender/prefab/curishia_bartender_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapeの`Shrink_UpperLeg`,`Shrink_Knee`,`Foot_flat`を100に設定。
   * `Necklace`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

<!-- ### ユリスフィアちゃん
1. lilToon, ユリスフィアちゃん, Modular Avatarのパッケージを先にインポート。
2. bartender.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ユリスフィアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/YRISPHERE/Prefab/PhysBone/YRISPHERE_改変用素体_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/bartender/prefab/yrisphere_bartender_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapesの`Foot_Heel`,`Leg_offf`を0に設定。
   * BodyのBlendShapesの`UpperLeg_off`,`knee_off`を100に設定。
   * UnderwearのBlendShapesの`gather_off`を100に設定。
   * `kneehigh`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。 -->

<!-- ### エミスティアちゃん
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. bartender.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/bartender/prefab/emistia_bartender_MA.prefab`を配置。
5. アバターを調整
   * BodyのBlendShapeの`Knee_high`を100に設定。
   * `Kemono`,`Shoes`,`Tights`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。 -->

## 更新履歴
2023/9/13 v1.3.0
* キュリシアちゃんの衣装に腰回りを細くするシェイプキーを追加。
* キュリシアちゃんの衣装のメッシュを微修正。
* キュリシアちゃんの衣装にグローブを追加。

2023/9/5 v1.2.0
* エルキュナ2ちゃん、リミリアちゃんの衣装に腰回りを細くするシェイプキーを追加。
  * bartender_braces, bartender_shirt, bartender_tie, bartender_waistcoatに`Waist_thin`を追加しています。

2023/8/20 v1.1.0
* エルキュナ2ちゃん、リミリアちゃんの対応を追加。

2023/8/20 v1.0.0
* 販売開始。

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】<br>
https://drive.google.com/file/d/1dzaVaYLGRfY2COpq8fsOosz1_CSrYmyg/view?usp=sharing

【English】<br>
https://drive.google.com/file/d/1XCKejCyeTufnIuchK8Wh8lkR1Hr2xnov/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/