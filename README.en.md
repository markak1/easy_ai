<div align="center">

# EASY-AI

**AI Model Unified Access Platform**

</div>

## About

EASY-AI is an AI model relay and management platform supporting unified access, distribution, and billing for mainstream LLMs.

## Features

- **Multi-Model Support** — OpenAI, Claude, Gemini, DeepSeek, Qwen, and more
- **OpenAI-Compatible API** — Standardized API, drop-in replacement
- **Channel Management** — Multi-channel auto-switching, automatic retry on failure
- **User Permission System** — Token grouping, model restrictions, usage analytics
- **Billing & Top-up** — Flexible quota management and cost accounting

## Deploy

```bash
git clone https://github.com/markak1/easy_ai.git
cd easy_ai
docker-compose up -d
```

Visit `http://localhost:3000` after deployment.

## Tech Stack

- **Backend**: Go (Gin)
- **Frontend**: React + TypeScript + TailwindCSS
- **Container**: Docker / Docker Compose

## License

[AGPL-3.0](./LICENSE)
