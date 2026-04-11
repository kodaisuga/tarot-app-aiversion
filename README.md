# タロット占いアプリ

## セットアップ

```bash
npm install
npm run dev
```

## Vercelへのデプロイ

1. GitHubにプッシュ
2. [vercel.com](https://vercel.com) でリポジトリを連携
3. 自動デプロイ完了

## ファイル構成

```
tarot-app/
├── public/
│   └── images/      # タロットカード画像 (78枚)
├── src/
│   ├── App.jsx      # メインアプリ
│   └── main.jsx     # エントリーポイント
├── index.html
├── package.json
├── vite.config.js
└── vercel.json
```
