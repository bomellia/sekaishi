# 思想史・章別穴埋め問題集

第1〜9章の穴埋め問題集（全27セット・396問）の再修正版です。

## ファイル構成

- `docs/index.html` — GitHub Pagesで公開する学習ビュアー。HTML単体で動作します。
- `index.html` — ビュアーの複製（リポジトリ内の参照用）。
- `materials/questions.txt` — 問題集（リポジトリ内のみ）。
- `materials/answers.txt` — 解答集（リポジトリ内のみ）。
- `materials/memo_with_supplements.txt` — 元メモの全ての本文行を残し、章末に短い補足を追記した版（リポジトリ内のみ）。

## GitHub Pages設定

- Settings → Pages → Build and deployment
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/docs**
- Save

通常の公開先URL: https://bomellia.github.io/sekaishi/

## 公開範囲と検索回避

リポジトリはPrivateのままにしますが、GitHub Pagesで公開した `docs/index.html` は誰でもURLで閲覧できます。検索エンジンにインデックス登録しないよう `noindex` を設定していますが、非公開アクセス制御ではありません。

`/docs` のみを公開するため、`/materials` 配下のTXTファイルはPagesから直接配信しません。ただし、ビュアーのHTML/JavaScriptには解答データが含まれており、閲覧者はそれを取得できます。

GitHub Pro等、PrivateリポジトリからPagesを公開できる対応プランが必要です。
