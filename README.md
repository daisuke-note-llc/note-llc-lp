# NOTE LLC Website Refresh

NOTE LLC公式サイトの静的HTML/CSS/JavaScript版プロトタイプです。

## ファイル構成

- `index.html` — 全ページ構造、本文、SEO/OGP/JSON-LD
- `css/styles.css` — レスポンシブデザイン
- `js/main.js` — モバイルメニュー、ヘッダー状態、年表示
- `assets/hero.jpg` — ライブ会場写真
- `assets/hi_ace.jpg` — DriveShare車両写真
- `CLAUDE.md` — Claude Codeが毎回参照するプロジェクトルール
- `PROMPT.md` — Claude Codeへ渡す初回・修正・公開前プロンプト
- `CNAME` — GitHub Pagesのカスタムドメイン

## ローカル確認

ビルドは不要です。プロジェクト直下で簡易サーバーを起動します。

```bash
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` を開いてください。

## Claude Code

macOSでは公式のネイティブインストールまたはHomebrewを使用できます。

```bash
brew install --cask claude-code
cd /path/to/note-llc-refresh
claude
```

最初に `PROMPT.md` の「Claude Codeに最初に渡すプロンプト」を貼り付け、計画を確認してから実装させてください。

## 公開前に確認する項目

- 公開済み情報だけが掲載されているか
- 各リリース・記事・SNSのURLが正しいか
- Instagramリンクを追加する場合は公式URLを確認したか
- OGP画像URLが公開環境と一致しているか
- GitHub Pagesの公開ブランチとCNAME設定
