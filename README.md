# Ryo Nihonyanagi / 二本柳亮

AI pathfinder from Tokyo. I teach AI agents at SHIFT AI, help teams adopt Claude Code and Codex at 10xc, and build my own agent workspace in the open.

AI の水先案内人。SHIFT AI で AI エージェントを教え、10xc で Claude Code / Codex の導入を支援しながら、自分の仕事も AI エージェントたちと回しています。

## 🧠 CerebraLOS — memory and a shared workspace for AI agents

**v4.0.0 "The Hub"** → [cerebralos-org/cerebralos](https://github.com/cerebralos-org/cerebralos)

A local brain that consolidates memory overnight, plus a hub on your own Cloudflare account where Claude Code, Codex, Gemini, Grok, ChatGPT and Grok Bot share context, take tasks from one board, and leave a run record you can actually check.

- Task board that routes work to the right AI, with approval gates for anything that posts, sends or spends
- Run records: who did it, the full output, sources and the raw model output
- Live "now" board and work locks so agents don't collide
- Remote MCP (OAuth 2.1), PWA with push notifications, Slack reports

## 🎙 on-air-deck

[on-air-deck](https://github.com/ryonihonyanagi-cloud/on-air-deck) — a native macOS broadcast desk that mixes mic, BGM and jingles for live streams and webinars.

## How I build

Most of what you see here is built together with Claude Code and Codex: I design and review, agents implement and test, and CerebraLOS keeps the context between sessions.
