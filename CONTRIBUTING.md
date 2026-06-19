# Contributing to BuilderIO/skills

Thank you for your interest in contributing! We welcome contributors of all types — code, tests, documentation, and design — and appreciate your time and effort.

This document explains how to report issues, propose changes, and get your pull requests reviewed and merged quickly.

---

## Table of contents

- How can I contribute?
- Code of conduct
- Filing issues
- Proposing changes (pull requests)
- Development setup
- Tests and CI
- Code style & commit messages
- Review process & expectations
- License

---

## How can I contribute?

You can help in many ways:

- Report bugs with a minimal reproducible example.
- Add or improve tests and documentation.
- Fix bugs and implement small features via PRs.
- Review other people's PRs.

If you're unsure where to start, check the repository issues and look for labels like `good first issue` or `help wanted`.

## Code of conduct

This project follows an inclusive code of conduct. Please be respectful and considerate in all interactions. If there is no CODE_OF_CONDUCT.md in this repo yet, please follow standard community etiquette (be constructive, assume good intent, and be patient).

## Filing issues

When filing an issue, please include:

- A clear, descriptive title.
- A concise description of the problem or request.
- Steps to reproduce (minimum reproducible example preferred).
- Expected vs. actual behavior.
- Environment details (OS, Node version, browser if relevant).
- Any relevant logs, stack traces, or screenshots.

If you're proposing a feature, explain the use case and suggested API or UX.

---

## Proposing changes (Pull Requests)

Follow these steps to propose changes:

1. Fork the repository and create a branch with a descriptive name (e.g. `fix/null-email-parsing` or `feat/auth-retry`).
2. Keep changes small and focused — one logical change per PR. Smaller PRs get reviewed faster.
3. Update or add tests for your change. If you change behavior, add tests that show the old (failing) behavior and the new (passing) behavior.
4. Run linters/formatters and make sure the code builds and tests pass locally.
5. Open a pull request with a clear title and a short summary. Use this structure in the PR body:

   - Summary (one-line)
   - Why (why this change is needed)
   - What changed (bullet list)
   - How to test (steps)
   - Notes (migrations, breaking changes)

6. Request reviews from specific maintainers or teams and explain what you want reviewed (logic, tests, docs).

We recommend creating draft PRs for early feedback on larger changes.

## Development setup

1. Clone and install dependencies:

   git clone https://github.com/BuilderIO/skills.git
   cd skills
   npm install

2. Create a feature branch:

   git checkout -b feat/your-feature

3. Run linters and tests locally (see Tests and CI section).

Adjust these commands if the repository uses Yarn, pnpm, or another package manager.

## Tests and CI

- Add unit/integration tests for any behavioral change.
- Keep tests deterministic and fast when possible.
- Ensure the CI is green before requesting a review. CI failures slow down reviews and merging.

If CI or linting fails for your PR, fix the issues locally and push an update.

## Code style & commit messages

- Follow the existing code style. Use the project's linter and formatter configuration (Prettier/ESLint) if present.
- Keep commits focused and meaningful. Squash WIP/fixup commits before final review if appropriate.
- Use conventional commit messages where possible, for example:

  - feat: add new feature
  - fix: bugfix
  - docs: documentation only changes
  - test: adding or updating tests
  - chore: build or tooling changes

## Review process & expectations

- Request reviews from 1–2 relevant reviewers. Mention specific files or areas to check in your PR description.
- Be responsive to review comments — reply with context, update code, or ask clarifying questions.
- Keep PRs small so reviewers can finish quickly (aim for ~10–30 minutes of review time).
- If you disagree with feedback, explain your reasoning with examples and tests and be open to compromise.

## License

By contributing, you agree that your contributions will be licensed under this project's license.

---

Thank you for helping improve BuilderIO/skills — we appreciate your contributions!
