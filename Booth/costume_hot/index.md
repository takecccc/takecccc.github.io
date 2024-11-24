---
title: Hot Denim
html:
   toc: true
---

# Hot Denim

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
* VRCSDK 3.7.4
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.8.3
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.10.9

## 対応アバター
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.2
* [ユリスフィアちゃん](https://skymy.booth.pm/items/3486694) v1.4.1
* [キュリシアちゃん](https://skymy.booth.pm/items/3990670) v1.1.2
* [ミコミアちゃん](https://skymy.booth.pm/items/5967855) v2.5
* [ルナールちゃん](https://booth.pm/ja/items/5319407) v1.18
* [シュカちゃん](https://studio7tsuki.booth.pm/items/6227036) v1.04
<!-- * [リミリアちゃん](https://skymy.booth.pm/items/4365043) v1.0.8 -->
<!-- * [エルキュナ2ちゃん](https://skymy.booth.pm/items/4926689) v1.6 -->

## 導入方法

### 共通手順
1. lilToon, Modular Avatar, 各アバターのパッケージを先にインポート。
2. hot.unitypackageをインポート。

### エミスティアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_emistia_MA.prefab`を配置。
3. アバターを調整
   * `Shoes`,`Tights`,`Underwear`を非表示にし、TagをEditorOnlyに変更。

### ユリスフィアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ユリスフィアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/YRISPHERE/Prefab/PhysBone/YRISPHERE_改変用素体_PhysBone.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_yrisphere_MA.prefab`を配置。
3. アバターを調整
   * `Underwear`を非表示にし、TagをEditorOnlyに変更。

### キュリシアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) キュリシアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/CURISHIA/Prefab/CURISHIA_改変用素体.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_curishia_MA.prefab`を配置。
3. アバターを調整
   * `Underwear`を非表示にし、TagをEditorOnlyに変更。

<!-- ### リミリアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) リミリアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/LIMILIA/Prefab/LIMILIA_改変用Prefab.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_limilia_MA.prefab`を配置。
3. アバターを調整
   * `Kemono`を非表示にし、TagをEditorOnlyに変更。-->

<!-- ### エルキュナ2ちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エルキュナ2ちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/ERUQYUNA2/Prefab/ERUQYUNA2_素体Variant.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_eruqyuna2_MA.prefab`を配置。
3. アバターを調整
   * `Kemono`を非表示にし、TagをEditorOnlyに変更。-->

### ミコミアちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ミコミアちゃんの素体prefab<br>
   `Assets/SKYMY_Workshop/03_Avatar/MIKOMIA/Prefab/MIKOMIA_OriginalSotai2_kisekae.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_mikomia_MA.prefab`を配置。
3. アバターを調整
   * `Underwear`と`Mi_Drawers`を非表示にし、TagをEditorOnlyに変更。

### ルナールちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) ルナールちゃんの素体prefab<br>
   `Assets/_Studio_7tsuki/7st01_Renard/着せ替え/7st01_Renard_Base Variant.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_renard_MA.prefab`を配置。
3. アバターを好みで調整

### シュカちゃん
1. 衣装を着せる素体をHierarchyに配置。<br>
   ex) シュカちゃんの素体prefab<br>
   `Assets/_Studio_7tsuki/7st02_Choucas/Custom_Prefab/_Default/7st02_Choucas MA_Base.prefab`
2. Hierarchy上のアバター直下に`Assets/Takec/Costume/hot/prefab/hot_renard_MA.prefab`を配置。(ルナールちゃんと共通素体です。)
3. アバターを好みで調整

## 更新履歴
2024/11/24 v1.6
* AnimationやMenuを整理。
* ユリスフィアちゃんの対応を追加。

2024/11/21 v1.5.2
* シュカちゃんの説明を追加。(Webのみ更新)

2024/11/18 v1.5.1
* エミスティアちゃんのグローブを修正。

2024/11/17 v1.5.0
* エミスティアちゃんの対応を追加。

2024/10/4 v1.4.0
* ルナールちゃんの対応を追加。

2024/9/15 v1.3.0
* マテリアルを調整
* おまけとしてグローブを追加

2024/9/11 v1.2.0
* 胸のサイズのシェイプキーを追加
* メッシュを微調整

2024/9/11 v1.1.0
* ミコミアちゃんの対応を追加

2024/9/8 v1.0.0
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