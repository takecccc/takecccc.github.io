---
title: 【エミスティアちゃん対応】巫女装束
html:
   toc: true
---

# 【エミスティアちゃん対応】巫女装束

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* Clothの頂点数およびPhysBoneのコンポーネント数によってVeryPoorとなります。

使用アセット
* lilToon ( https://lilxyzw.github.io/lilToon/#/ )
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
  * 着替えアニメーション、エクスプレッションメニュー
  * コンポーネント設定済み衣装prefab
* 衣装テクスチャファイル(clip, psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2022.3.6f1
* VRCSDK 3.5.2
* [エミスティアちゃん](https://skymy.booth.pm/items/2992265) v1.3.2
* [lilToon](https://lilxyzw.github.io/lilToon/#/) v1.7.3
* [Modular Avatar](https://modular-avatar.nadena.dev/ja/) 1.9.10

## 導入方法
1. lilToon, EMISTIAちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_miko.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に衣装プレファブを配置
   * Clothあり `Assets/Takec/EMISTIA/model/miko/prefab/EMISTIA_miko_with_Cloth_MA.prefab`
   * Clothなし `Assets/Takec/EMISTIA/model/miko/prefab/EMISTIA_miko_without_Cloth_MA.prefab`
5. アバターを調整
   * `Shoes`, `Tights`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/4/27 v2.0.0
* Modular Avatarを使用したセットアップに変更。
* Clothコンポーネントを削除したプレファブを追加。

2022/5/2 v1.1.0
* 白衣のメッシュ・ウェイトを調整。
* 袴のコライダーを調整。
* DynamicBoneからPhysBoneに変更。
* シェーダーをlilToonに変更。

2022/4/2 v1.0.1
* 暗いワールドで白が濁ってしまっていたので、マテリアルのパラメーターを調整。

2021/12/29 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1kwpkWisCMrpzhSp752vwUBGMzQdh3y0Q/view?usp=sharing

【English】
https://drive.google.com/file/d/1lDOjR48FnlI6TwZElyzlUsdPh7tLInTE/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
