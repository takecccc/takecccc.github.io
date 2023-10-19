---
title: 【エミスティアちゃん対応】ウィッチスタイル3Dモデル
---

# 【エミスティアちゃん対応】ウィッチスタイル3Dモデル

## 概要
本アセットはSKYMY Workshop様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* Modular Avatar ( https://github.com/bdunderscore/modular-avatar/releases )を使用。
* Clothの頂点数によってVeryPoorとなります。

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
  * コンポーネント設定済み衣装prefab
* 衣装テクスチャファイル(psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 3.4.1
* [エミスティアちゃん v1.3.1](https://skymy.booth.pm/items/2992265)
* [lilToon v1.4.1](https://lilxyzw.github.io/lilToon/#/)
* [Modular Avatar 1.8.1](https://modular-avatar.nadena.dev/ja/)

## 導入方法
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_bikini.unitypackageをインポート。
3. 衣装を着せたい素体をHierarchyに配置。  
   ex) エミスティアちゃんの素体prefab。  
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone`
4. 衣装およびMagicWandのプレファブをHierarchyの素体直下に配置。
   * `Assets/Takec/EMISTIA/model/witch/prefab/EMISTIA_witch_MA.prefab`
   * `Assets/Takec/EMISTIA/model/witch/prefab/magic_wand_MA.prefab`
5. 素体データの調整
   1. `Shoes`,`Tights`を非表示に設定してTagをEditorOnlyに変更。
   2. `Kemono`のBlendShapesの`Tail_cover_off`を100に設定。
6. VRChat SDKのControlPanelからアップロード。

## 更新履歴
2023/10/19 v2.0.1
* Magic Wandの挙動がおかしかったので修正。

2023/7/9 v2.0.0
* ディティールアップ
* ModularAvatarを使用したセットアップに変更。
* ローブの裾が若干短くなりました。
* 袖まくり追加

2022/5/5 v1.4.0
* ローブを上と下に分割してClothの負荷軽減
* DynamicBoneからPhysicsBoneに変更。
* ClothとPhysicsBoneの設定を全面的に見直し。
* ローブ上側のウェイトを微修正。
* シェーダーをlilToonに変更。

2021/11/6 v1.3.0
* 改変済みのエミスティアちゃんに組み込みやすいようにコンポーネント設定済みの衣装のprefabを追加しました。
* fbxにリーフボーンを追加しました。
* AvatarAssemblerでの結合に対応するため、既存のボーンではなく、追加のボーンにコライダーを追加するように変更しました。
* 帽子にシェイプキーを入れていたのにウェイト付けしていなかったので、帽子用のボーンを追加してDynamicBoneを設定しました。

2021/10/18 v1.2.0
* Cloth設定したprefabを追加。

2021/10/13 v1.1.0
* 杖を追加

2021/10/8 v1.0.0
* 販売開始

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1MYEyUG8i4yDnW1XpkjFKEh9BFKqZ6Le1/view?usp=sharing

【English】
https://drive.google.com/file/d/1Kq4lXTFnAUv1EH7kDBNRl0eeNsrFHmz3/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
