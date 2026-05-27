<div align="center">

# EASY-AI

**AIモデル統合アクセスプラットフォーム**

</div>

## 概要

EASY-AIは、主要なLLMの統合アクセス、配布、課金をサポートするAIモデル中継・管理プラットフォームです。

## 機能

- **複数モデル対応** — OpenAI、Claude、Gemini、DeepSeek、Qwenなど
- **OpenAI互換API** — 標準化されたAPI
- **チャンネル管理** — 自動切替、失敗時の自動リトライ
- **ユーザー権限管理** — トークングループ化、モデル制限
- **課金・チャージ** — 柔軟なクォータ管理とコスト会計

## デプロイ

```bash
git clone https://github.com/markak1/easy_ai.git
cd easy_ai
docker-compose up -d
```

デプロイ後 `http://localhost:3000` にアクセスしてください。

## ライセンス

[AGPL-3.0](./LICENSE)
