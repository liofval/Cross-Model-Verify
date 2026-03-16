# Cross-Model-Verify

同じ要件の家計簿（Kakeibo）アプリを、異なるAIコーディングアシスタントで生成し、その出力を比較するプロジェクト。

**https://liofval.github.io/Cross-Model-Verify/**

## 比較対象

| | Claude版 | Codex版 |
|---|---|---|
| ツール | Claude Code (Opus) | OpenAI Codex CLI |
| フレームワーク | React 19 + TypeScript + Vite 8 | React 19 + TypeScript + Vite 6 |
| チャートライブラリ | Recharts 3 | なし |
| スタイリング | CSS Modules | CSS Modules |
| データ保存 | localStorage | localStorage |

## 構成

```
index.html          # ポータル画面
claude-version/     # Claude版ビルド成果物
codex-version/      # Codex版ビルド成果物
```

## ソースコード

各バージョンのソースコードは別リポジトリで管理:

- Claude版: [kakeibo_claude](https://github.com/liofval/kakeibo_claude)
- Codex版: [kakeibo_codex](https://github.com/liofval/kakeibo_codex)
