# AIラクスル

無料で使えるAIツールを紹介するブログサイトです。`site/` フォルダの中身がそのまま公開用のファイルです。

## 公開手順(Cloudflare Pages)

1. このフォルダをGitHubリポジトリにする(GitHub Desktopなどでこのフォルダを新規リポジトリとして公開)
2. Cloudflareにログイン → Workers & Pages → Pages → 「Gitに接続」で上記リポジトリを選択
3. ビルド設定:
   - ビルドコマンド: (空欄のまま)
   - ビルド出力ディレクトリ: `site`
4. デプロイすると `https://(プロジェクト名).pages.dev` で公開されます

## フォルダ構成
- `site/index.html` … トップページ
- `site/about.html` … 運営者情報・免責事項
- `site/posts/` … 記事ページ
- `site/style.css` … 共通デザイン
- `marketing_plan.md` … 集客・運用プラン
