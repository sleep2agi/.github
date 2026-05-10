<img width="2019" height="779" alt="image" src="https://github.com/user-attachments/assets/6f3473fe-df4e-426f-b6d9-d1e1915c7f93" />

# sleep2agi

> 多 Agent 协作，一行命令。让 Claude / GPT / MiniMax 在你电脑上一起干活。

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/sleep2agi/agent-network/blob/main/LICENSE)
[![npm version](https://img.shields.io/npm/v/@sleep2agi/agent-network.svg)](https://www.npmjs.com/package/@sleep2agi/agent-network)
[![Docs](https://img.shields.io/badge/docs-anet.sh-009e7e.svg)](https://anet.sh)

## [Agent Network](https://github.com/sleep2agi/agent-network)

一个 npm 包装好 Hub、Dashboard、Agent 三件套：

```bash
npm install -g @sleep2agi/agent-network

anet hub start          # 起 CommHub Server
anet hub dashboard      # 起 Web UI（http://localhost:3000）
anet demo debate        # 6 角色辩论赛 一键跑
```

### 套件

| 包 | 角色 |
|---|---|
| [`@sleep2agi/agent-network`](https://www.npmjs.com/package/@sleep2agi/agent-network) | `anet` CLI（启动 Hub / Dashboard / Agent / Demo） |
| [`@sleep2agi/commhub-server`](https://www.npmjs.com/package/@sleep2agi/commhub-server) | 通信中枢（MCP + REST + SSE，SQLite/Postgres） |
| [`@sleep2agi/agent-node`](https://www.npmjs.com/package/@sleep2agi/agent-node) | Agent 运行时（Claude Code CLI / Claude Agent SDK / Codex SDK） |
| [`@sleep2agi/agent-network-dashboard`](https://www.npmjs.com/package/@sleep2agi/agent-network-dashboard) | Web Dashboard（Next.js，4 主题） |

### 核心特性

- 🚀 **一行装完** — `npm i -g @sleep2agi/agent-network`，三步就位
- 🧠 **三种 Runtime** — Claude Code CLI / Claude Agent SDK / Codex SDK
- 🤝 **七家 LLM** — Claude / GPT / MiniMax / DeepSeek / GLM / Kimi / 书生 Intern
- 🎙️ **一键 Demo** — `anet demo debate` 6 角色辩论 / `anet demo socialmedia` 4 角色社媒工厂
- 🌐 **跨机器组网** — Hub 绑 0.0.0.0，其他机器 SSE 实时双向
- 🩺 **自动迁移** — `anet doctor --fix` 修旧配置不丢 session
- 🔒 **本地优先** — SQLite 跑你机器，可换 PostgreSQL，可选 ntok_ 网络隔离

## 链接

- 📖 文档：[anet.sh](https://anet.sh)
- 💻 仓库：[github.com/sleep2agi/agent-network](https://github.com/sleep2agi/agent-network)
- 💬 讨论：[GitHub Discussions](https://github.com/orgs/sleep2agi/discussions)
- 🔒 安全：[Security Advisories](https://github.com/sleep2agi/agent-network/security/advisories/new)

## License

Apache-2.0 © 2025-2026 sleep2agi
