# CLAUDE.md

This file provides guidance to Claude Code (and other AI assistants) when working with this repository.

## Repository Overview

This is **Benja106's GitHub profile README repository**. Because the repository name (`Benja106`) matches the account owner's username, GitHub treats it as a special repo: the contents of `README.md` are rendered directly on the user's public GitHub profile page (`https://github.com/Benja106`).

There is no application code, build system, package manifest, or test suite — the entire repository currently consists of a single file:

```
README.md   # Rendered on https://github.com/Benja106
```

## Working with this Repository

- **Primary file**: `README.md` is the only content that matters. Treat edits to it as edits to a public-facing personal profile page, not as application source code.
- **No build/test/lint tooling**: Do not introduce package.json, CI workflows, linters, etc. unless the user explicitly asks for them — this repo is intentionally minimal.
- **Markdown + emoji conventions**: The README follows the standard GitHub profile template style — short bullet points prefixed with emoji (👋, 👀, 🌱, 💞️, 📫, etc.) introducing the person. Keep this tone/format when editing unless the user asks for a redesign.
- **HTML comments**: The `<!--- ... --->` block at the bottom is GitHub's default boilerplate explaining the special nature of this repo. It's safe to remove if the user wants a cleaner profile, but don't remove it incidentally.

## Common Requests

- **Updating profile info** (bio bullets, links, badges, stats widgets, etc.): edit `README.md` directly.
- **Adding visual elements** (GitHub stats cards, skill icons, social badges): these are typically `<img>`/markdown image embeds pointing at third-party badge services (e.g., shields.io, github-readme-stats). Confirm with the user before adding external image dependencies, since they load from third-party servers on every profile view.
- **Significant restructuring or adding actual project code**: confirm with the user first, since that would change the nature of this repository from a profile page to a real project.

## Conventions for AI Assistants

- Keep changes scoped to `README.md` (and this `CLAUDE.md`) unless the user asks for something new.
- Don't fabricate biographical details, links, or stats — ask the user for real content to fill in placeholders like "I'm interested in ...".
- Since this file is publicly visible, avoid including any sensitive personal information (private email, phone numbers, addresses) unless the user explicitly requests it.
