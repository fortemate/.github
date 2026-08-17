# Contributing to Fortemate

Thank you for your interest! This is the default contributing guide for the
organization. **If the repository you want to contribute to has its own
`CONTRIBUTING.md`, follow that one** — several repositories carry additional
requirements (notably a CLA, see below).

## The short version

1. For features and bug fixes, open an issue first (context, objective, definition
   of done). Routine work — docs, refactoring, CI — can skip the issue.
2. Branch from `main` using the naming convention `<type>/<short-description>`,
   optionally `<type>/<id>-<short-description>` to link an issue. Types:
   `task` / `feat` / `bug` for issue-driven work, `refactor` / `chore` / `docs` /
   `ci` / `test` / `perf` for the rest. There is no `fix/` type — bug fixes go on
   `bug/`.
3. Most repositories use [mise](https://mise.jdx.dev/) as the task runner: run
   `mise run format` on modified code and make sure `mise run check` passes locally
   before opening a pull request.
4. In the pull request, explain *why* before *what*, state how the change was
   verified, and include `Closes #<id>` when the branch references an issue.
5. Everything written into repositories — code, comments, commits, pull requests,
   issues — is in English.

## Licensing and the CLA

The platform repositories (engine, web app, backend, analytics, the Java house
bot) are **AGPL-3.0** and require a one-time signature of the repository's
Contributor License Agreement with your first pull request. Signing is
self-service: add yourself to `.github/cla-signatures.json` in the same pull
request — the `CI: CLA` check verifies it automatically. You keep the copyright to
your work; the CLA is what keeps the project's open-core model legally sound.

The starter kits (`dicechess-bot-python`, `dicechess-bot-typescript`,
`dicechess-bot-random`, `dicechess-reference-bot`, `dicechess-bot-runtime`) are
**MIT** — fork freely, no CLA required.

**Building your own bot does not require signing anything.** The CLA applies only
to contributions sent back to these repositories.

## Questions

See [SUPPORT.md](SUPPORT.md) for where to ask.
