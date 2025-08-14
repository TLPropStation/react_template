---
name: '🤖 Code Generation Request'
about: 'claudeにコード生成を依頼するためのテンプレートです'
title: '[CODEGEN] '
labels: 'enhancement, codegen'
assignees: ''
---

## 📋 概要

<!-- 生成してほしいコードの概要を1-2文で説明してください -->

## 🎯 目的

<!-- なぜこのコードが必要なのか、解決したい課題は何か -->

## 📝 詳細な要件

### 入力

<!-- 必要な入力データや引数の型・形式を明確に記載 -->

```typescript
// 例:
interface InputData {
  name: string;
  age: number;
}
```

### 出力

<!-- 期待される出力の型・形式を明確に記載 -->

```typescript
// 例:
interface OutputData {
  message: string;
  isValid: boolean;
}
```

### 処理内容

<!-- どのような処理を行うか、ステップごとに記載 -->

1.
2.
3.

## 🛠️ 技術仕様

- **言語/フレームワーク**: <!-- 例: TypeScript, React, Node.js -->
- **対象ファイル**: <!-- 例: src/utils/validation.ts -->
- **依存関係**: <!-- 使用するライブラリやパッケージ -->

## ✅ 受け入れ条件

<!-- このコードが完成したと判断するための条件 -->

- [ ] 指定された入力に対して正しい出力を返す
- [ ] エラーハンドリングが適切に実装されている
- [ ] TypeScriptの型定義が完全である
- [ ] 単体テストが作成されている

## 📌 サンプルコード

<!-- 期待する動作の例やテストケース -->

```typescript
// 使用例:
const input = { name: 'John', age: 25 };
const result = yourFunction(input);
console.log(result); // { message: "Hello John", isValid: true }
```

## 🚫 制約事項

<!-- やってはいけないこと、避けるべきパターン -->

-
-

## 📎 参考資料

<!-- 参考になるドキュメントや既存コードへのリンク -->

- ***

## 🤖 Claude AIへの依頼

<!-- issueを作成後、以下のコメントをコピーして投稿してください -->

@claude 上記の仕様に基づいてコードを生成してください。以下の点に注意してください：

- TypeScriptの型定義を完全に実装すること
- エラーハンドリングを適切に行うこと
- 単体テストも一緒に作成すること
- 既存のコードスタイルに合わせること
