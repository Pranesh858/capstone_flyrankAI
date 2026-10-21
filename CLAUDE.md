# Capstone conventions

This file is for Cursor and other AI coding assistants. Follow it for every change in this repository.

## Project

- Name: `capstone_flyrankAI`
- Owner: Pranesh Chandrasekhar
- Purpose: FlyRank AI internship capstone — AI-assisted development as the core skill, then a public portfolio artifact.

## Stack

- Node.js LTS, Git, Cursor
- TypeScript for app and tooling code
- Python only when a later phase needs RAG, eval, or ML work
- Prefer the standard library and a small dependency set

## Git

- Conventional Commits: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`
- Imperative, lowercase description after the type
- One logical change per commit
- Never commit `.env`, secrets, or `node_modules`

## Code

- Keep files small and named by purpose
- Match existing style; do not reformat unrelated files
- Add a short README note when a new command or env var is required
- Verify Node and Git commands on Windows (PowerShell) as well as bash snippets

## AI workflow

- Critique before expanding scope
- Apply one concrete improvement when asked to review docs
- Do not invent product features that are not in the current phase
