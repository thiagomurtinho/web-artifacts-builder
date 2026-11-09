---
name: chatgpt-web-artifacts
description: Build complex React/TypeScript/Tailwind/shadcn web artifacts using Anthropic scripts.
---

# ChatGPT adaptation

Read `../web-artifacts-builder/SKILL.md`. Preserve upstream scripts and license. For complex UI, initialize with `scripts/init-artifact.sh <project>`, implement React UI, then bundle from project root using `scripts/bundle-artifact.sh`. Verify `bundle.html` before delivery. Requires external shell with Node/npm; plugin cannot execute shell by itself or replace ChatGPT native renderer. Inspect scripts before running; do not expose secrets.
