<div align="center">

# EASY-AI

**AI 模型统一接入平台**

</div>

## 简介

EASY-AI 是一个 AI 模型中转与管理平台，支持多种主流大模型的统一接入、分发与计费管理。

## 功能特性

- **多模型统一接入** — OpenAI、Claude、Gemini、DeepSeek、Qwen 等主流模型
- **OpenAI 兼容接口** — 标准化 API，无缝替换
- **渠道管理与负载均衡** — 多渠道自动切换、失败重试
- **用户权限体系** — Token 分组、模型限制、用量统计
- **计费与充值** — 灵活的额度管理与成本核算

## 部署

### Docker Compose（推荐）

```bash
git clone https://github.com/markak1/easy_ai.git
cd easy_ai

# 修改 docker-compose.yml 配置后启动
docker-compose up -d
```

部署完成后访问 `http://localhost:3000` 即可使用。

### 环境变量

| 变量名 | 说明 | 默认值 |
|--------|------|--------|
| `SESSION_SECRET` | 会话密钥（多机部署必填） | - |
| `SQL_DSN` | 数据库连接字符串 | SQLite |
| `REDIS_CONN_STRING` | Redis 连接字符串（可选） | - |
| `STREAMING_TIMEOUT` | 流式超时时间（秒） | `300` |

### 数据库支持

- SQLite（默认）
- MySQL ≥ 5.7.8
- PostgreSQL ≥ 9.6

## 技术栈

- **后端**：Go (Gin)
- **前端**：React + TypeScript + TailwindCSS
- **容器化**：Docker / Docker Compose

## 许可证

[AGPL-3.0](./LICENSE)
