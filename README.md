# TeaPilot

Native Gitea client for Android 10+ and Wear OS by Tracht Digital Solutions.

## Project status

Repository bootstrap only. Application code, build configuration and the complete product specification have not yet been imported. No installable application is available.

## Scope

- Kotlin, Jetpack Compose and Compose for Wear OS.
- Shared Android and Wear OS core modules with a native watch interface.
- Official Gitea APIs, isolated server/account data and secure local storage.
- No integrated AI, telemetry, Google Play Services dependency or WebView fallbacks.
- Android and Wear OS only; no Apple platforms or tooling.
- Gitea Actions on Linux runners for future CI and release gates.
- Intended license: Apache License 2.0; the full license must be included before source distribution.

## Development handoffs

Implementation tasks belong in `codex-handoffs/TASK-XXXX-short-title.md`.
Before implementing a task, read the central specification at
`docs/specification/TEAPILOT_SPEC.md`, project rules, project status and gap analysis.
The complete specification is currently missing; this README does not replace it.

Claude Code is the primary development agent. Codex handles explicit handoffs and
records implementation, validation, remaining risks and review requirements in a
`CODEX-ERGEBNIS` section. Do not report unexecuted checks as passing.
