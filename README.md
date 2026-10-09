# 成績優先度ボード（案件管理システムに統合済み）

このリポジトリで動かしていた求人広告の運用ダッシュボードは、
**案件管理システムに統合しました。** 中身は
[rdbusinessunit/anken-kanri](https://github.com/rdbusinessunit/anken-kanri) の
`board/` に移っています。

| | URL |
|---|---|
| 新しい場所 | https://rdbusinessunit.github.io/anken-kanri/board/ |
| 以前のURL | https://rdbusinessunit.github.io/airwork-kanri/ （転送ページだけ残しています） |

以前のURLを開くと自動的に新しい場所へ移動します。ブックマークの差し替えをお願いします。

## データについて

Supabaseは統合の前後で同じプロジェクト・同じ `jobs` テーブルを使っています。
**移行は行っていないので、これまで蓄積したデータはそのまま表示されます。**

## このリポジトリについて

転送ページ（`index.html`）だけを残しています。アプリ本体と手順書は
統合先の `board/` にあります。過去のコードは、このリポジトリのコミット履歴
（`4cb32ea` 以前）から参照できます。
