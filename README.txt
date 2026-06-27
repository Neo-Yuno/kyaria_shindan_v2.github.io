# 職種マップ診断 RIASECプロトタイプ

## GitHub Pagesで公開する手順

1. このフォルダ内の `index.html`、`style.css`、`script.js`、`.nojekyll` をリポジトリの一番上に置く
2. GitHubの `Settings` → `Pages` を開く
3. `Build and deployment` の `Source` を `Deploy from a branch` にする
4. `Branch` を `main`、フォルダを `/ (root)` にして保存する
5. 表示されたURLで、トップページに診断画面が出ることを確認する

`index.html` がリポジトリ直下にない場合、GitHub PagesのトップURLでは表示されません。フォルダごとアップロードした場合は、フォルダの中身をリポジトリ直下へ移動してください。

## ファイル構成

- `index.html`: 画面構造
- `style.css`: デザイン
- `script.js`: 質問、分岐、スコア計算、結果表示
- `.nojekyll`: GitHub Pagesで静的ファイルをそのまま配信するための設定

## 使い方

1. 「診断を始める」を押す
2. 質問に答える
3. 結果画面でRIASECスコア、職種カード、授業、資格、大学中にやることを見る

回答データは保存されず、ブラウザ内だけで処理されます。
