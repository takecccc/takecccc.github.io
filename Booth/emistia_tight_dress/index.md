---
title: 【エミスティアちゃん対応】 タイトドレス
---

# 【エミスティアちゃん対応】 タイトドレス3Dモデル

## 概要
本アセットはSKYMY工房様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した
衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* マテリアルを6パターン同梱。
  * lilToon( https://github.com/lilxyzw/lilToon )使用 x5
  * Standard使用PBR x1
* Modular Avatar( https://github.com/bdunderscore/modular-avatar/releases )を使用。

## 内容物
* Unitypackageファイル
  * fbx
  * マテリアル
  * コンポーネント設定済み衣装prefab
* テクスチャファイル(psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRChat SDK 3.1.13
* エミスティアちゃん v1.2.4
* lilToon v1.3.7
* Modular Avatar 1.4.5

## 導入方法
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_tight_dress.unitypackageをインポート。
3. 衣装を着せたい素体をHierarchyに配置。  
   ex) エミスティアちゃんの素体prefab。  
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. 衣装のプレファブをHierarchyに配置。
   `Assets/Takec/EMISTIA/model/tight_dress/Prefabs/EMISTIA_tight_dress_MA.prefab`
5. 結合データの調整
   1. `Shoes`を非表示とし、Tagを`EditorOnly`に変更。
   2. `Tights`等の表示・非表示をお好みで調整
   3. 衣装のSkinned Mesh RendererのProbesのAnchor Overrideに素体のAnchor Overrideを指定。
6. VRChat SDKのControlPanelからアップロード。

## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/18S8kIVgrfRC-oOJECe5DtyOEGdMHWRGc/view?usp=sharing

【English】
https://drive.google.com/file/d/1TG7jY8RYam9WUyCwWwhQjb5oxVlbbPHG/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
