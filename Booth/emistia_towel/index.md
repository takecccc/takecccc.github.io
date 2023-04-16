---
title: 【エミスティアちゃん対応】バスタオル
---
# 【エミスティアちゃん対応】バスタオル

## 概要
本アセットはSKYMY Workshop様のエミスティアちゃん( https://skymy.booth.pm/items/2992265 )に対応した衣装の3Dモデルです。
※本データにエミスティアちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* Modular Avatar ( https://github.com/bdunderscore/modular-avatar/releases )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* lilToon v1.3.7
* 衣装テクスチャファイル(psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRChat SDK 3.1.13 
* エミスティアちゃん v1.2.4
* lilToon v1.3.7
* Modular Avatar 1.4.5

## 導入方法
1. lilToon, エミスティアちゃん, Modular Avatarのパッケージを先にインポート。
2. EMISTIA_towel2.unitypackageをインポート。
3. 衣装を着せたい素体をHierarchyに配置。  
   ex) エミスティアちゃんの素体prefab。  
   `Assets/SKYMY_Workshop/03Avatar/EMISTIA/Prefab/EMISTIA_改変用Prefab_PhysBone.prefab`
4. 衣装のプレファブをHierarchyに配置。
   `Assets/Takec/EMISTIA/model/towel2/Prefabs/EMISTIA_towel2_MA.prefab`
5. 結合データの調整
   1. `Shoes`,`Tights`,`Underwear`を非表示とし、Tagを`EditorOnly`に変更。
   2. `Kemono`,`Necklace`等の表示・非表示をお好みで調整
   3. `towel`のSkinned Mesh RendererのProbesのAnchor Overrideに素体のAnchor Overrideを指定
6. VRChat SDKのControlPanelからアップロード。

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/1ECzTULHH5bhWR940fDPa13TvSzkB0Iw1/view?usp=sharing

【English】
https://drive.google.com/file/d/1qce6b8RCHrhKxsItNAoi07gSyvl5_vYr/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/
