# Aethr Deploy (MCP Server)

Production readiness checks for AI agents (Claude Desktop, Cursor, etc.). It gives your agent awareness of deploy blockers: missing env vars, absent Dockerfile, no .env example, and more (extensible).

## Features (v0.1)
- `check_deploy_readiness`: basic scan for package.json, Dockerfile, .env.example; returns issues.
- Designed to expand: env var diffing, Dockerfile analysis, config validation, health check suggestions.

## Install
```bash
npm install -g @aethr/deploy
