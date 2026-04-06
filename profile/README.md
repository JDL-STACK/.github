# JDL STACK

Full-stack SAP development platform and aviation dashboard, built with Express 5, React 19, MongoDB, and SAP AI Core.

## Apps

| | App | Description | Version |
|---|-----|-------------|---------|
| **[Orchestrair](https://github.com/JDL-STACK/orchestrair)** | SAP Control Tower | AI-powered ABAP/RAP code analysis, MCP tools, BTP management | `v0.6.0` |
| **[SkyDesk](https://github.com/JDL-STACK/skydesk)** | Aviation Dashboard | ATPL theory study, PPL currency tracking, flight preparation | `v0.1.0` |

## Shared

| | Package | Description | Version |
|---|---------|-------------|---------|
| **[Common](https://github.com/JDL-STACK/common)** | Shared Packages | `@jdl/backend-core` + `@jdl/frontend-core` | `v1.0.0` |
| **[Workspace](https://github.com/JDL-STACK/workspace)** | Monorepo Root | npm workspaces + git submodules | `v0.1.0` |

## Stack

Express 5 &middot; React 19 &middot; MongoDB (Mongoose 9) &middot; Vite 8 &middot; SAP AI Core &middot; MCP &middot; Plain CSS

## Architecture

```
workspace/               npm workspaces root
  common/                @jdl/backend-core + @jdl/frontend-core
  orchestrair/           SAP dev platform (dev/prod branches)
  skydesk/               Aviation dashboard
```
