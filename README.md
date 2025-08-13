# React + TypeScript + Vite テンプレート

モダンなReactアプリケーション開発のための包括的なテンプレートリポジトリです。

## 🚀 特徴

- **React 19**
- **TypeScript**
- **Vite**
- **Vitest**
- **Storybook**
- **ESLint + Prettier**
- **React Hook Form + Zod**

## 📦 技術スタック

### コア技術

- React 19.1.1
- TypeScript 5.8.3
- Vite 7.1.2
- Node.js 24.x

### テスト環境

- Vitest 3.2.4
- Testing Library
- Playwright
- カバレッジレポート

### 開発ツール

- Storybook 9.1.2
- ESLint 9.33.0
- Prettier 3.6.2
- pnpmパッケージマネージャー

## 🛠️ セットアップ

### 前提条件

- Node.js 24.x（.nvmrcファイルを使用）
- pnpm 10.14.0

### インストール

```bash
# このテンプレートをクローン
git clone [your-repo-url]
cd [your-project-name]

# 依存関係をインストール
pnpm install

# 開発サーバーを起動
pnpm dev
```

## 📜 利用可能なスクリプト

```bash
pnpm dev          # 開発サーバーを起動
pnpm build        # プロダクションビルド
pnpm preview      # ビルドのプレビュー
pnpm lint         # ESLintを実行
pnpm lint:fix     # ESLintの問題を自動修正
pnpm format       # Prettierでフォーマット
pnpm test         # テストを実行
pnpm coverage     # カバレッジレポートを生成
pnpm storybook    # Storybookを起動
```

## 🏗️ プロジェクト構成

```
.
├── .storybook/          # Storybook設定
│   ├── main.ts
│   ├── preview.ts
│   └── vitest.setup.ts
├── public/              # 静的アセット
│   └── vite.svg
├── src/
│   ├── assets/          # 画像アセット
│   │   └── react.svg
│   ├── stories/         # Storybookストーリーとコンポーネント
│   │   ├── assets/      # Storybook用画像
│   │   ├── Button.tsx
│   │   ├── Button.stories.ts
│   │   ├── Header.tsx
│   │   ├── Header.stories.ts
│   │   ├── Page.tsx
│   │   ├── Page.stories.ts
│   │   ├── Configure.mdx
│   │   ├── button.css
│   │   ├── header.css
│   │   └── page.css
│   ├── App.tsx          # メインAppコンポーネント
│   ├── App.css          # Appスタイル
│   ├── main.tsx         # アプリケーションエントリーポイント
│   ├── index.css        # グローバルスタイル
│   └── vite-env.d.ts    # Vite型定義
├── .gitignore           # Git除外設定
├── .node-version        # Node.jsバージョン指定
├── .nvmrc               # Node.jsバージョン指定（nvm用）
├── .prettierrc          # Prettier設定
├── eslint.config.js     # ESLint設定
├── index.html           # HTMLエントリーポイント
├── package.json         # プロジェクト設定
├── pnpm-lock.yaml       # 依存関係ロックファイル
├── tsconfig.json        # TypeScript設定（ルート）
├── tsconfig.app.json    # アプリケーション用TS設定
├── tsconfig.node.json   # Node.js用TS設定
├── vite.config.ts       # Vite設定
└── vitest.shims.d.ts    # Vitest型定義
```

## 🔧 設定

### VSCode統合

最適な開発体験のためのVSCode設定が含まれています：

- 保存時のESLint自動修正
- JS/TS以外のファイルのPrettierフォーマット
- TypeScript統合

### TypeScript

追加の安全性チェックを含む厳格モードが有効：

- `strict: true`
- `noUnusedLocals: true`
- `noUnusedParameters: true`
- `noFallthroughCasesInSwitch: true`

### テスト

Vitestの設定内容：

- Playwrightによるブラウザテスト
- カバレッジレポート
- React Testing Library統合

## 🚀 デプロイ

プロダクション用にビルド：

```bash
pnpm build
```

ビルド出力は`dist`ディレクトリに生成され、静的ホスティングサービスにデプロイできます。

---
