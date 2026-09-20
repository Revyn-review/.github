<div align="center">

# Revyn

**AI-powered pull request reviews — automatic, inline, and instant.**

[![Website](https://img.shields.io/badge/Website-revyn--dev.vercel.app-black?style=flat-square)](https://revyn-dev.vercel.app)
[![GitHub App](https://img.shields.io/badge/GitHub%20App-Install-181717?style=flat-square&logo=github)](https://github.com/apps/revyn-dev)

</div>

---

## What is Revyn?

Revyn connects to your GitHub repositories and automatically reviews every pull request — catching bugs, flagging risky changes, and summarizing what a PR actually does, before a human reviewer even opens it.

No new workflow to learn. Reviews show up as normal inline PR comments, right where the issue is.

## How it works

1. Install the Revyn GitHub App on your repo
2. Open a pull request
3. Revyn fetches the diff, reviews it with an LLM, and posts inline comments + a summary — usually within seconds
4. Track review history from the [dashboard](https://revyn-dev.vercel.app)

## Repositories

| Repo | Description |
|---|---|
| [`revyn`](https://github.com/Codewithpabitra/Revyn) | Server — GitHub App integration, webhook handling, AI review pipeline (Fastify + BullMQ + Groq) |
| `revyn-dashboard` | Dashboard — Next.js frontend for connecting repos and viewing review history |

## Tech stack

Fastify · TypeScript · BullMQ · Redis · Groq · Prisma · PostgreSQL (Neon) · Next.js · Clerk · Tailwind CSS

## Status

Actively in development. Built as a solo project — feedback and issues welcome.

---

<div align="center">
<sub>Built by <a href="https://github.com/Codewithpabitra">@Codewithpabitra</a></sub>
</div>
