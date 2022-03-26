# compornent（共通部品）

## イメージ画像
<img width="395" alt="image" src="https://user-images.githubusercontent.com/99580997/160230125-48867ac7-5f63-4757-8a93-2a240e897100.png">
<img width="778" alt="image" src="https://user-images.githubusercontent.com/99580997/160230131-665a78fc-4268-47a5-8b82-ea460c6e2d49.png">
<img width="944" alt="image" src="https://user-images.githubusercontent.com/99580997/160230139-10579072-cd42-4f86-963c-0b1f1da0151a.png">


## 概要

- ホバー時、擬似要素で背景の色を変更する。
- 擬似要素の layer が想定どおりにできないので、再検証。
- 親要素`button`
- 子要素`span`
- w3c html/css チェック ok
- `onclick`を使用（`a`タグを使用すると w3c チェックでエラーとなる為）
- box からはみ出る部分は`overflow: hidden;`を使用。

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- xxx

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="756" alt="image" src="https://user-images.githubusercontent.com/99580997/160230152-d5cd89eb-0a7c-4283-85be-4a1155a9a87a.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/

## portfolio url:

- https://css-md-0036.wtb.cfbx.jp/
- <img width="1506" alt="image" src="https://user-images.githubusercontent.com/99580997/160230161-85f9acb8-e737-47bb-aaf2-1a802f174505.png">


## 参考にしたサイト

- 【CSS】マウスオーバーで疑似要素がスライドインするアニメーション
- https://into-the-program.com/hover-animation8/
- css translate の使い方！transform の translate の３ D 移動
- https://owl-view.com/css/2579/
- HTML のボタンでリンク作成 2: button タグ
- https://style.potepan.com/articles/22374.html

## 更新履歴

- 2022/3/26 初版 作成完了(ホバー時、擬似要素で背景の色を変更する。onclick、transform: translate3d();で実装)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
