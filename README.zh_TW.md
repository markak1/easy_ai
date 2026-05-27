<div align="center">

# EASY-AI

**AI 模型統一接入平台**

</div>

## 簡介

EASY-AI 是一個 AI 模型轉發與管理平台，支援多種主流大型語言模型的統一接入、分發與計費管理。

## 功能特性

- **多模型統一接入** — OpenAI、Claude、Gemini、DeepSeek、Qwen 等主流模型
- **OpenAI 相容介面** — 標準化 API，無縫替換
- **通道管理與負載平衡** — 多通道自動切換、失敗重試
- **使用者權限體系** — Token 分組、模型限制、用量統計
- **計費與儲值** — 靈活的額度管理與成本核算

## 部署

```bash
git clone https://github.com/markak1/easy_ai.git
cd easy_ai
docker-compose up -d
```

部署完成後存取 `http://localhost:3000` 即可使用。

## 技術棧

- **後端**：Go (Gin)
- **前端**：React + TypeScript + TailwindCSS
- **容器化**：Docker / Docker Compose

## 授權條款

[AGPL-3.0](./LICENSE)
