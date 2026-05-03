# Contributing to claude-kit

Thanks for your interest in contributing!

## How to contribute

1. Fork the repo and create a branch from `main`
2. Make your changes
3. Run `npm test && npm run lint` — both must pass
4. Open a pull request with a clear description

## Development setup

```bash
git clone https://github.com/buildproven/claude-kit.git
cd claude-kit
npm install
./install.sh      # symlinks into ~/.claude/
```

## Conventions

- Conventional commits are enforced: `feat:`, `fix:`, `docs:`, `chore:`, etc.
- No `eslint-disable` comments — fix the root cause
- No `any` TypeScript, no `--no-verify`
- Tests live in `scripts/__tests__/` — add one for any logic you touch

## What's in scope

- Bug fixes and improvements to existing commands, skills, agents, and scripts
- New commands or skills that fit the free-tier scope (see `EXTENSION-ARCHITECTURE.md`)
- Documentation improvements

## What belongs in claude-kit-pro

Autonomous workflow features, session management, and premium skills are in the paid tier. PRs adding these to claude-kit will be redirected.

## Reporting security vulnerabilities

See [SECURITY.md](SECURITY.md).
