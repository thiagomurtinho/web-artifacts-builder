# Web Artifacts Builder for ChatGPT

Original Anthropic skill and scripts: `skills/web-artifacts-builder/`, plus root mirror.

Upstream: https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder
Commit: `2c5958ecac7cee2b583967a2c4981d0f4a75c579` (2026-11-09).

ChatGPT adaptation: `skills/chatgpt-web-artifacts/SKILL.md`.

Local: run `bash scripts/init-artifact.sh example`, edit React project, then run `bash scripts/bundle-artifact.sh` in project. Scripts require a shell and Node/npm; ChatGPT plugin alone does not execute them or replace its native renderer.
