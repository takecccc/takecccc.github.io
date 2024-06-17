---
title: 【エミスティアちゃん対応】ウェストコートスタイル
html:
   toc: true
---

# 【エミスティアちゃん対応】ウェストコートスタイル

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

使用アセット
* lilToon ( https://lilxyzw.github.io/lilToon/#/ )
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
  * 着替えアニメーション、エクスプレッションメニュー
  * コンポーネント設定済み衣装prefab
* 衣装テクスチャファイル(clip, psd, png) ※psdはclipstudioで保存したものです。
* モデルファイル(fbx)

## 動作確認環境
* Unity 2022.3.22f1
* VRChat SDK 3.6.1
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.2
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.7.3
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.9.10

## 導入方法
1. lilToon, EMISTIAちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_wastcoat.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に衣装プレファブを配置
   * `Assets/Takec/EMISTIA/model/wastcoat/prefab/EMISTIA_waistcoat_MA.prefab`
5. アバターを調整
   * `Body`のBlendShapesの`thigh_small`を50に設定。
   * `Kemono`のBlendShapesの`Tail_cover_off`を100に設定。
   * `Underwear`のBlendShapesの`Underwear_race_off`,`Underwear_hirahira_off`を100に設定。
   * `Shoes`,`Tights`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/6/17 v2.0.0
* Modular Avatarを用いたセットアップに変更。
* ShaderをUTSからlilToonに変更。

2022/4/25 v1.1.0
* お尻のボーン構造に不具合があったのを修正。
* 本体v1.2.1に対応したprefabを追加。

2022/4/2 v1.0.1
* カラーバリエーションを追加。

2022/4/2 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1lvE-Q90Fb984myXpgNEvfNrXU6ePjZvS/view?usp=sharing

【English】
https://drive.google.com/file/d/1--ZxPmoC7heyp158hm1B4_K1tXioeHzU/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
