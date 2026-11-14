# product_screens マニュアル

## 概要
公開中のWebプロダクトをiframeで並べ、実画面を見ながら移動できる一覧ページ。
`projects_index`（表形式の一覧）の画面版。

## 構成
- `index.html` … 本体（1ファイル）。カードごとに `<iframe>`＋「開く ↗」リンク

## 更新方法
1. `index.html` にカード（`<article class="card">`）を追加・削除する
2. 先頭の件数表示（projects / live screens）と各見出しの `LIVE SCREENS` 数を合わせる
3. commit → push（GitHub Pagesに反映）

## 注意
- iframeが空白になる場合、相手側が埋め込みを禁止している（X-Frame-Options等）。「開く ↗」から開く
- privateリポジトリのURLは載せない
