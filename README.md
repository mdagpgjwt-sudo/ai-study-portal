# AI導入 LAB — 90日学習ポータル

AI業務自動化の習得を目指す学習サイト。教材、確認問題、実装ラボ、90日ロードマップ、進捗記録を含みます。

## 公開サイト

GitHub Pagesを有効化すると、次のURLで利用できます。

https://mdagpgjwt-sudo.github.io/ai-study-portal/

**初回公開設定（1回だけ）**

1. [Settings → Pages](https://github.com/mdagpgjwt-sudo/ai-study-portal/settings/pages) を開く
2. **Build and deployment → Source** を **Deploy from a branch** にする
3. **Branch** は `main`、フォルダーは `/(root)` を選び **Save**
4. 公開後は同じURLにアクセスする

## 教材の更新

`index.html` がサイト本体です。このファイルを更新して `main` にコミットすると、GitHub Pagesが自動で最新版を公開します。更新のたびにHTMLやZIPをダウンロードし直す必要はありません。

`sample_orders.csv` は実装ラボ用の架空の練習データです。

## 学習進捗の保存

学習記録はブラウザの `localStorage` に保存されます。**同じブラウザ・同じURL** でアクセスすると、教材更新後も通常は記録が残ります。別PC、別ブラウザ、別ドメインには自動同期されません。ブラウザのデータ消去でも消えるため、サイト内のJSONエクスポートで定期的にバックアップを取ってください。

**今までローカルのHTMLで学習していた場合**、古いページでJSONバックアップを書き出し、公開サイト上でインポートしてください。公開サイトへ自動移行はされません。

## 公開範囲と機密情報

このリポジトリとGitHub Pagesは公開されています。APIキー、パスワード、顧客データ、個人情報、業務上の機密情報は追加しないでください。公開デモでは架空データを使用してください。
