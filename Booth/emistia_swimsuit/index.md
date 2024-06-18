---
title: 【エミスティアちゃん対応】スクール水着
html:
   toc: true
---

# 【エミスティアちゃん対応】スクール水着

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。

※本データにエミスティアちゃん本体のデータは含まれておりません。

* lilToon使用。

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
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
2. EMISTIA_swimsuit.unitypackageをインポート。
3. 衣装を着せる素体をHierarchyに配置。<br>
   ex) エミスティアちゃんの素体prefab。<br>
   `Assets/SKYMY_Workshop/03_Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. Hierarchy上のアバター直下に衣装プレファブを配置
   * `Assets/Takec/EMISTIA/model/swimsuit/prefab/EMISTIA_swimsuit_MA.prefab`
   * `Assets/Takec/EMISTIA/model/swimsuit/prefab/EMISTIA_swimsuit2_MA.prefab`
5. アバターを調整
   * `Kemono`のBlendShapesの`Tail_cover_off`を100に設定。
   * `Shoes`,`Tights`,`Underwear`を非表示にし、TagをEditorOnlyに変更。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2024/6/18 v2.0.0
* Modular Avatarを使用したセットアップに変更。
* スクール水着と競泳水着のprefabを分離。
* 競泳水着にmatcapを追加。

2022/5/28 v1.2.1
* bounding boxとanchor overrideの設定漏れを修正。

2022/5/26 v1.2.0
* 競泳水着verを追加。
* 対応エミスティアちゃんをv1.2.2に更新。
* 着替えアニメーションを追加。
* シェーダーをlilToonに変更。

2022/4/25 v1.1.0
* prefabを本体v1.2.1に対応。

2022/4/22 v1.0.2
* たまーーにお尻が貫通してたのを、ウェイトの微修正と生地の厚みを増したことで対策しました。

2022/4/22 v1.0.1
* シェイプキー(BlendShapes)が消えていたので修正。

2022/4/20 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1eCLWgAJOitrlDzURzJae1AOm5GxFEqSS/view?usp=sharing

【English】
https://drive.google.com/file/d/1gaD1UXZlV9uH35CEpM2wvA1D6nAOcf1O/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
