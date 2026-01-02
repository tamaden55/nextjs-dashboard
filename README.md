# Next.js カウンターアプリ

シンプルなカウンターアプリです。Next.js の学習用プロジェクトとして作成しました。

## デモ

本番環境: https://nextjs-dashboard-olive-delta-49.vercel.app

## 機能

- カウントの増加 (+1)
- カウントのリセット (0)
- ダークモード対応（システム設定に自動対応）
- レスポンシブデザイン（PC・タブレット・スマホ対応）

## 技術スタック

- **フレームワーク**: Next.js 15.5.9
- **言語**: TypeScript
- **スタイリング**: Tailwind CSS
- **ホスティング**: Vercel
- **バージョン管理**: Git + GitHub

## ローカル開発

### 必要な環境

- Node.js 18.17 以上
- npm または pnpm

### セットアップ

1. リポジトリをクローン

```bash
git clone https://github.com/tamaden55/nextjs-dashboard.git
cd nextjs-dashboard
```

2. 依存関係をインストール

```bash
npm install
```

3. 開発サーバーを起動

```bash
npm run dev
```

4. ブラウザで開く

http://localhost:3000 にアクセス

## ファイル構造

```
nextjs-dashboard/
├── app/
│   ├── layout.tsx      # ルートレイアウト
│   └── page.tsx        # メインページ（カウンターアプリ）
├── public/             # 静的ファイル
├── .dev/               # 開発用ドキュメント
└── README.md           # このファイル
```

## デプロイ

このプロジェクトは Vercel にデプロイされています。

`main` ブランチへの push で自動的に本番環境が更新されます。

### 手動デプロイ（初回のみ）

1. GitHub にプッシュ

```bash
git add .
git commit -m "コミットメッセージ"
git push origin main
```

2. Vercel でプロジェクトをインポート

https://vercel.com/new からリポジトリを選択してデプロイ

## 学習リソース

- [Next.js ドキュメント](https://nextjs.org/docs) - Next.js の機能と API
- [Next.js チュートリアル](https://nextjs.org/learn) - インタラクティブな学習コース
- [Tailwind CSS ドキュメント](https://tailwindcss.com/docs) - スタイリングの参考

## ライセンス

MIT
