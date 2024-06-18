---
title: 【エミスティアちゃん対応】メイド服
html:
   toc: true
---

# 【エミスティアちゃん対応】メイド服

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。

※本データにエミスティアちゃん本体のデータは含まれておりません。

* PhysBoneのコンポーネント数によってVeryPoorとなります。
* lilToonを使用。

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
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.9.13

## 導入方法
1. lilToon, EMISTIAちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_maid.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に衣装プレファブを配置
   * `Assets/Takec/EMISTIA/model/maid/prefab/EMISTIA_maid_MA.prefab`
5. アバターを調整
   * `Kemono`のBlendShapesの`Tail_cover_off`を100に設定。
   * `Shoes`,`Tights`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/6/18 v2.0.0
* Modular Avatarを使用したセットアップに変更。

2022/5/2 v1.1.0
* ボーン構造の不備を修正。
* DinamicBoneからPhysBoneに変更。

2022/2/18 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1490X82WDZWltYxXnNgBkFVA3W2aGO7Om/view?usp=sharing

【English】
https://drive.google.com/file/d/1GlKjeGzMR-FElClTlOm0mP_n93ql2jDQ/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
