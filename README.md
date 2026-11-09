# Web Artifacts Builder — Unofficial ChatGPT Adaptation

**Unofficial community adaptation. Not affiliated with or endorsed by Anthropic or OpenAI.**

Original skill, scripts, and component archive: [Anthropic skills / web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder), pinned to upstream commit `2c5958ecac7cee2b583967a2c4981d0f4a75c579`. The original files are mirrored under `skills/web-artifacts-builder/` and at the repository root. Our modifications are in `skills/chatgpt-web-artifacts/` and the plugin manifests.

## Limitations

This is **not** Claude Artifacts and does **not** reproduce Claude live preview, editing, or execution within ChatGPT. The ChatGPT plugin is an instruction adapter; it does not automatically execute bundled scripts. Use an authorized shell with Node.js 18+ and pnpm to build projects.

## Local usage

1. Review the scripts before executing them; they install npm dependencies.
2. Run `bash scripts/init-artifact.sh example`.
3. Develop the generated React/TypeScript project.
4. From inside the generated project run `bash ../scripts/bundle-artifact.sh` (adjust the relative path if needed).
5. Open the resulting `bundle.html` in a browser.

## License and attribution

The imported Anthropic skill and scripts are distributed under Apache License 2.0; see [LICENSE.txt](LICENSE.txt). The bundled shadcn/ui component sources may have their own upstream notices and dependency licenses; review them for your redistribution and production use. This repository preserves upstream files and identifies adaptation-specific additions.
