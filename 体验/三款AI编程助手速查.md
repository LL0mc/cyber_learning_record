# OpenClaw / Hermes Agent / MiMo Code 速查

## OpenClaw

| 操作         | 命令                                                                |
| ---------- | ----------------------------------------------------------------- |
| 启动 Gateway | `npm start` (在 `openclaw\` 目录下)                                   |
| 启动 TUI     | `npm run tui`                                                     |
| 打开 Web 控制台 | `npx openclaw dashboard` (浏览器打开 `http://127.0.0.1:18789/control`) |
| 停止 Gateway | `Ctrl+C` (前台运行) 或 `npx openclaw gateway stop` (后台服务)              |

## Hermes Agent

| 操作 | 命令 |
|------|------|
| 启动交互式聊天 | `python hermes` (在 `hermes-agent\hermes-agent\` 下, venv 内) |
| 一次性查询 | `python hermes -z "问题"` |
| Web Dashboard | `python hermes dashboard` (浏览器打开 `http://127.0.0.1:9119/`) |
| 停止 | `Ctrl+C` 或 `python hermes dashboard --stop` |

## MiMo Code

| 操作 | 命令 |
|------|------|
| 启动 TUI | `npm start` (在 `mimo-code\` 目录下) |
| 启动 API Server | `npm run serve` (端口 4096) |
| 一次性查询 | `npx mimo run "问题" --model mimo/mimo-auto` |
| 停止 | `Ctrl+C` |
