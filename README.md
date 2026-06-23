# facebook-page-manager — Manage Facebook Pages via Meta Graph API

> List, post, and moderate your Facebook Pages through the Meta Graph API. No browser needed — pure API calls for posts, comments, and page management.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
facebook-page-manager provides Node.js scripts for managing Facebook Pages through the Meta Graph API. It handles the full page management cycle: listing your managed pages, posting text/photos/links, reading existing posts, and handling comments (list, reply, hide, delete). Setup involves creating a Meta App, configuring OAuth, and running an auth script that walks through the token flow.

## Features
- **List pages** — all pages you manage
- **Post content** — text, photo, and link posts
- **List posts** — browse existing page posts
- **Comment management** — list / reply / hide / delete comments
- **OAuth auth flow** — guided token setup via `node scripts/auth.js login`

## Usage / Quick Start
```bash
# One-time setup
cp .env.example .env          # fill in App ID + App Secret
cd scripts && npm install
node auth.js login             # follow prompts to authorize
```
Setup: create Meta App → configure Facebook Login OAuth → add yourself as Developer → run auth script.

## Trigger Keywords (OpenClaw)
publish to Facebook page, check page posts, handle comments, Facebook page manager

## Related Skills
- [facebook-mcp-server](https://github.com/NachaFromMars/facebook-mcp-server) — MCP server for Page management
- [facebook-humanmode](https://github.com/NachaFromMars/facebook-humanmode) — browser-based human-like automation

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
