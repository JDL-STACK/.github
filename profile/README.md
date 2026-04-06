# JDL STACK

Full-stack SAP development platform and aviation dashboard, built with Express 5, React 19, MongoDB, and SAP AI Core.

## Apps

| | App | Description | Version |
|---|-----|-------------|---------|
| **[Orchestrair](https://github.com/JDL-STACK/orchestrair)** | SAP Control Tower | AI-powered ABAP/RAP code analysis, MCP tools, BTP management | `v0.6.0` |
| **[SkyDesk](https://github.com/JDL-STACK/skydesk)** | Aviation Dashboard | ATPL theory study, PPL currency tracking, flight preparation | `v0.1.0` |
| **[JDL-STACK CMS](https://github.com/JDL-STACK/jdl-stack)** | Personal Website | Fastify 5 + Nunjucks SSR, bilingual CMS, product pages | `v1.0.0` |

## Shared

| | Package | Description | Version |
|---|---------|-------------|---------|
| **[Common](https://github.com/JDL-STACK/common)** | Shared Packages | `@jdl/backend-core` + `@jdl/frontend-core` | `v1.0.0` |
| **[Workspace](https://github.com/JDL-STACK/workspace)** | Monorepo Root | npm workspaces + git submodules | `v0.2.0` |

## Documentation

| Document | Description |
|----------|-------------|
| [Workspace README](https://github.com/JDL-STACK/workspace#readme) | Setup, structure, submodule management |
| [Orchestrair CLAUDE.md](https://github.com/JDL-STACK/orchestrair/blob/dev/CLAUDE.md) | Full architecture, GoF patterns, API reference |
| [SkyDesk CLAUDE.md](https://github.com/JDL-STACK/skydesk/blob/dev/CLAUDE.md) | Aviation app architecture and features |
| [JDL-STACK CMS CLAUDE.md](https://github.com/JDL-STACK/jdl-stack/blob/dev/CLAUDE.md) | CMS architecture, product pages, GoF patterns |

## Stack

Express 5 &middot; React 19 &middot; MongoDB (Mongoose 9) &middot; Vite 8 &middot; SAP AI Core &middot; MCP &middot; Plain CSS

## Architecture

```
workspace/               npm workspaces root
  common/                @jdl/backend-core + @jdl/frontend-core
  orchestrair/           SAP dev platform (dev/prod branches)
  skydesk/               Aviation dashboard
  jdl-stack/             Personal website CMS (independent repo)
```
