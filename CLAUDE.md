# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

This is the **GitHub profile README repo** for the user `KingPin` (the repo name matches the username, which is what makes it render on https://github.com/KingPin). It is content-only — there is no application code, no build system, no tests, and no lint configuration. Edits here are almost always to `README.md`.

## Repository contents

- `README.md` — the profile content GitHub renders on the user's page.
- `.github/workflows/snake.yml` — generates the contribution-graph snake animation (`github-snake.svg` + `github-snake-dark.svg`) on a daily cron and on every push to `main`, then publishes the SVGs to the `output` branch via `crazy-max/ghaction-github-pages`. The README references those SVGs by raw URL on the `output` branch, so the workflow must keep running for the animation to stay current. Don't delete the `output` branch.

## README structure conventions

The "⭐ Favorite Projects" section is organized into fixed category headings (DevOps & Infrastructure, Monitoring & Ops, Security & Privacy, AI & Automation, Games, Web & Self-hosted). When adding a project:

- Linked entries (`**[name](url)**`) point to either a public repo or a hosted page for that project; unlinked entries are intentionally private consulting / personal work shown for context. Don't add a link to an unlinked entry without confirming there is something public to point at (repo or hosted site).
- Keep the one-line description style: dash-separated, lowercase tech stack, no trailing period.
- Place new entries inside the most fitting category rather than inventing new sections.
