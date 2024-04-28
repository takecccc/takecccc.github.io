---
title: 【エミスティアちゃん対応】ロングドレス3Dモデル
html:
   toc: true
---

# 【エミスティアちゃん対応】ロングドレス3Dモデル

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://booth.pm/ja/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

使用アセット
* lilToon ( https://lilxyzw.github.io/lilToon/#/ )
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )

※Clothコンポーネントに使用しているメッシュの頂点数の関係でAvatarRankはVeryPoorとなります。ご承知ください。

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
  * 着替えアニメーション、エクスプレッションメニュー
  * コンポーネント設定済み衣装prefab
* 衣装テクスチャファイル(clip, psd, png) ※psdはclipstudioで保存したものです。
* モデルファイル(fbx)

## 動作確認環境
* Unity 2022.3.6f1
* VRCSDK 3.5.2
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.2
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.7.3
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.9.10

## 導入方法
1. lilToon, EMISTIAちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_long_dress.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に衣装プレファブを配置
   * `Assets/Takec/EMISTIA/model/long_dress/prefab/EMISTIA_long_dress_MA.prefab`
5. アバターを調整
   * `Shoes`, `Tights`を非表示にし、TagをEditorOnlyに変更。
   * `Kemono`のBlendShapeの`Tail_cover_off`を100に変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/4/28 v2.0.0
* Modular Avatarを使用したセットアップに変更。
* マテリアルをLilToonに変更。

2022/4/25 v1.1.0
* 本体v1.2.1に対応したprefabに入れ替え。

2021/11/1 v1.0.2
* 改変済みのエミスティアちゃんに組み込みやすいようにコンポーネント設定済みの衣装のprefabを追加しました。
* つま先のコンポーネントの設定を行うため、fbxにリーフボーンを追加しました。
* AvatarAssemblerでの結合に対応するため、既存のボーンではなく、追加のボーンにコライダーを追加するように変更しました。

2021/10/22 v1.0.1
* Material 1,2のテクスチャのWrap ModeがRepeatに設定されておりmipmapでテクスチャ境界が目立ってしまっていたのを修正。
* お尻と太腿のDBを無効化した上でシルエットを重視したコライダーに微調整。

2021/10/21 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/19qS5zGrgYI6hWntluS2HJcgUexLCiiHJ/view?usp=sharing

【English】
https://drive.google.com/file/d/18EJyUu6v255LiTWwz_S5v2reJE83fJ2-/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
