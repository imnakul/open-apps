---
name: Local Codex & Claude Analytics Ledger
repoUrl: https://github.com/imnakul/codex-analytics
projectType: real-app
category: developer-tools
stack: react
description: Local dashboard for Codex and Claude Code sessions, token usage, runtime, model comparisons, and API-equivalent cost estimates.
platforms:
  - web
licenses:
  - mit
links:
  github: https://github.com/imnakul/codex-analytics
tags:
  - codex
  - claude-code
  - usage-analytics
  - token-usage
  - local-first
seo:
  title: Codex Claude Ledger - Open Source AI Usage Dashboard
addedAt: 2026-10-20
submittedBy: imnakul
---

## Why it is worth listing

This dashboard reads existing local Codex state and Claude Code session records
to compare token usage, active runtime, models, and API-equivalent cost estimates.
It runs in a local browser and does not call an AI model or upload session data.
Pricing can be edited locally, and individual sessions expose task and tool details.

The Next.js, React, TypeScript, and Zod codebase includes read-only SQLite access,
JSONL parsing, provider switching, and synthetic ingestion and pricing tests.
It offers a small application to study local data ingestion and developer analytics.

Cost estimates are not subscription bills. Installation requires Node.js 24 or
newer and local Codex or Claude Code records. Internal provider formats can change.

Maintainer submission: the submitting account maintains this project.
