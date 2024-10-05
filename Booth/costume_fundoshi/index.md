---
title: ふんどしセット
html:
   toc: true
---

# ふんどしセット

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
* VRCSDK 3.7.1
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.7.3
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.10.0

## 対応アバター
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.2
* [ユリスフィアちゃん](https://skymy.booth.pm/items/3486694) v1.4.1
* [キュリシアちゃん](https://skymy.booth.pm/items/3990670) v1.1.2
* [リミリアちゃん](https://skymy.booth.pm/items/4365043) v1.0.8
* [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.6
* [ミコミアちゃん](https://skymy.booth.pm/items/5967855) v2.5
* [ルナールちゃん](https://booth.pm/ja/items/5319407) v1.18

## 導入方法

### エミスティアちゃん
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/PhysBone/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_emistia_MA.prefab`を配置。
5. アバターを調整
   * `Shoes`,`Tights`,`Underwear`を非表示にし、TagをEditorOnlyに変更。
   * `Kemono`のBlendShepesの`Tail_cover_off`を100に設定。
6. VRChat SDKのControlPanelからアップロード。

### ユリスフィアちゃん
1. lilToon, ユリスフィアちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ユリスフィアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/YRISPHERE/Prefab/PhysBone/YRISPHERE_改変用素体_PhysBone.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_yrisphere_MA.prefab`を配置。
5. アバターを調整
   * `Kneehigh`と`Underwear`を非表示にし、TagをEditorOnlyに変更。
   * `Body`のBlendShapesの`Foot_Heel`と`Leg_off`を0に設定。
6. VRChat SDKのControlPanelからアップロード。

### キュリシアちゃん
1. lilToon, キュリシアちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) キュリシアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/CURISHIA/Prefab/CURISHIA_改変用素体.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_curishia_MA.prefab`を配置。
5. アバターを調整
   * `Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### リミリアちゃん
1. lilToon, リミリアちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リミリアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/LIMILIA/Prefab/LIMILIA_改変用Prefab.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_limilia_MA.prefab`を配置。
5. アバターを調整
   * `Boots`,`Tights`,`Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### エルキュナ2ちゃん
1. lilToon, エルキュナ2ちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エルキュナ2ちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/ERUQYUNA2/Prefab/ERUQYUNA2_素体Variant.prefab`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_eruqyuna2_MA.prefab`を配置。
5. アバターを調整
   * `Underwear_er`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### ミコミアちゃん
1. lilToon, ミコミアちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ミコミアちゃんの素体prefab<br>
   `Assets/SKYMY_Workshop/03_Avatar/MIKOMIA/Prefab/MIKOMIA_OriginalSotai2_kisekae`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_mikomia_MA.prefab`を配置。
5. アバターを調整
   * `Mi_Body_Torso`のBlend Shapeの`Foot flat`を100に設定。
   * `Mi_Drawers`,`Mi_Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

### ルナールちゃん
1. lilToon, ルナールちゃん, Modular Avatarのパッケージを先にインポート。
2. fundoshi.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ルナールちゃんの素体prefab<br>
   `Assets/_Studio_7tsuki/7st01_Renard/着せ替え/7st01_Renard_Base Variant`
4. Hierarchy上のアバター直下に`Assets/Takec/Costume/fundoshi/prefab/fundoshi_renard_MA.prefab`を配置。
5. アバターを調整
   * `UnderWear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/10/5 v1.1.0
* さらしを上げるシェイプキーを追加。
* メッシュの微調整。
* メニューの誤爆リスク低減。

2024/9/29 v1.0.0
* 販売開始

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