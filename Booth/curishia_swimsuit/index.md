# 【キュリシアちゃん対応】スクール水着
この度はAtelier Takecにてご購入いただき誠にありがとうございます。

## 概要
本アセットはSKYMY Workshop様のキュリシアちゃん( https://skymy.booth.pm/items/3990670 )に対応した衣装の3Dモデルです。
※本データにキュリシアちゃん本体のデータは含まれておりません。

* lilToon ( https://github.com/lilxyzw/lilToon )を使用。
* AvatarTools( https://takec.booth.pm/items/3411988 )を使用。

## 内容物
* 衣装Unitypackageファイル
  * fbx
  * コンポーネント設定済み衣装prefab
  * マテリアル
* lilToon v1.3.2b Unitypackageファイル
  (開発用devブランチ fd547c4cfc37d194b05df22bb0934945f74ac9af)
* 衣装テクスチャファイル(clip, psd, png)
  ※psdはclipstudioで保存したものです。
  (clip,psdファイルは4096x4096で作成してありますが、pngは2048x2048で出力しています。)
* モデルファイル(fbx)

## 動作確認環境
* Unity 2019.4.31f1
* VRCSDK 2022.06.03.00.04
* キュリシアちゃん 1.0.0-r5
* lilToon v1.3.2b
* AvatarTools v2.2.3

## 導入方法
1. VRCSDK, キュリシアちゃん, lilToon, AvatarToolsのパッケージを先にインポート。
2. curishia_swimsuit.unitypackageをインポート。
3. ベースとなるモデルをHierarchyに配置。
   ex) キュリシアちゃんの素体prefab。
   `Assets/SKYMY_Workshop/03Avatar/CURISHIA/Prefab/CURISHIA改変用素体.prefab`
4. 衣装prefabをHierarchyに配置。
   `Assets/Takec/CURISHIA/swimsuit/curishia_swimsuit_prefab.prefab`,
   `Assets/Takec/CURISHIA/swimsuit/curishia_swimsuit2_prefab.prefab`
5. AvatarToolsで衣装を結合
   1. メニューからAvatarToolsのAvatarAssemblerを起動。
   2. AvatarAssemblerの`BaseObject`にHierarchyからベースモデルを指定。
   3. AvatarAssemblerの`CombineObjects`の`+`ボタンを押して枠を追加して、Hierarchyから衣装prefabを指定
   4. `Assemble!`ボタンを押すと結合したオブジェクトがHierarchyに配置されます。
6. **お好みに調整。**
   下着も非表示にするか削除する必要があります。
7. VRChat SDKのControlPanelからアップロード。


## 利用規約 Terms of Use
本アバターはVN3ライセンスにて公開しております。
規約は下記のリンクをご確認ください。

【日本語】
https://drive.google.com/file/d/18UaKBWdJkyN2uHj5iLtqxxR67uEqaWoG/view?usp=sharing

【English】
https://drive.google.com/file/d/1Nyj9H7NKeYYvILYXwNHgPh5RjmMnXCK_/view?usp=sharing

## その他
製作者
: takec

Twitter
: @takec_vrc

販売サイト
: https://takec.booth.pm/