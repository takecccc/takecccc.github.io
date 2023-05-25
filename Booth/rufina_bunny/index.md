---
title: 【Rufinaちゃん対応】 バニースーツ
---

# 【Rufinaちゃん対応】バニースーツ

## 概要
本アセットは仮想VoidCat様のRufinaちゃん( https://yueou.booth.pm/items/4670579 )に対応した衣装の3Dモデルです。  
※本データにRufinaちゃん本体のデータは含まれておりません。

* lilToon ( https://lilxyzw.github.io/lilToon/#/ )を使用。
* Modular Avatar ( https://modular-avatar.nadena.dev/ja/ )を使用。
* MeshDeleterWithTexture ( https://gatosyocora.booth.pm/items/1501527 )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* 衣装テクスチャファイル(psd, png)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 3.2.0
* [RufinaVRC_1.0.2](https://yueou.booth.pm/items/4670579)
* [lilToon v1.4.0](https://lilxyzw.github.io/lilToon/#/)
* [Modular Avatar 1.5.1](https://modular-avatar.nadena.dev/ja/)
* [MeshDeleterWithTexture beta 0.8.2](https://gatosyocora.booth.pm/items/1501527)

## 導入方法
1. lilToon, Modular Avatar, Rufinaちゃんを先にプロジェクトに追加。
2. rufina_bunny.unitypackageをインポート。
3. Rufinaちゃんの素体prefabに着せるだけであれば、設定済みのprefabを用意してあるのでHierarchyに配置して手順 7. へ  
   `Assets/Takec/Rufina/bunny/prefab/Rufina_bunny.prefab`
4. 衣装を着せたい素体をHierarchyに配置。  
   ex) Rufinaちゃんの素体prefab。  
   `Assets/Voidcat/Rufina/Prefabs/RufinaSotai.prefab`
5. 衣装のプレファブを素体直下に配置。
   `Assets/Takec/Rufina/bunny/prefab/rufina_bunny_MA.prefab`
6. 素体の調整1
   1. `Body2`のBlendShapeについて、次のように設定
       |key|value|
       |-|-|
       |BodyShrinkFoot_Left|100|
       |BodyShrinkFoot_Right|100|
       |BodyShrinkLowerLeg_Left|0|
       |BodyShrinkLowerLeg_Right|0|
       |BodyShrinkUpperLeg2_Left|0|
       |BodyShrinkUpperLeg2_Right|0|
       |BodyShrinkUpperLeg1_Left|0|
       |BodyShrinkUpperLeg1_Right|0|
       |BodyShrinkHips|0|
   2. `BodyEar`,`BodyTail`,`ClothNecklace`,`ClothTights`,`ClothUnder`を非表示とし、Tagを`EditorOnly`に変更。
7. 素体の調整2
   FootをShrinkしても飛び出てしまうので、メッシュを削除します。  
   Menu > GatoTool > MeshDeleter with Texture を起動し、`Body2`を選択した状態で`Asset/Takec/Rufina/bunny/material/Body2_footmask.png`を読み込んでメッシュを削除してください。
8. VRChat SDKのControlPanelからアップロード。

## 利用規約 Terms of Use
本衣装はVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】  
https://drive.google.com/file/d/1NKUMeoPwvnB_3Cq-J6mf0-rZkUivLuDp/view?usp=sharing

【English】  
https://drive.google.com/file/d/1LbFCYoALRWFl0t4saBlgyBCUZV4UWAVH/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/