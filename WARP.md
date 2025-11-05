# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

Repository status (auto-discovered)
- No build/test/config files detected (e.g., no package manifests like package.json/pyproject.toml/go.mod, no Dockerfile, no test configs).
- No README.md, CLAUDE.md, Cursor rules (.cursor/rules/ or .cursorrules), or Copilot instructions (.github/copilot-instructions.md) found.
- Git reports an empty working tree (no tracked or untracked project files).

Commands
- Build: Not defined yet — add once a toolchain is introduced (e.g., npm run build, dotnet build, mvn package, cargo build, go build, or python build via pyproject).
- Lint/format: Not defined yet — add after introducing tooling (e.g., eslint/biome/prettier, ruff/black/flake8, golangci-lint, ktlint, swiftlint).
- Tests: Not defined yet — document once a framework is added (e.g., npm test, pnpm vitest, pytest, go test ./..., mvn test, cargo test).
- Run a single test: Document per framework once adopted (e.g., vitest path/to/file.test.ts -t "name", pytest path::TestClass::test_case, go test -run "Name").

High-level architecture and structure
- Not applicable yet: no source directories (e.g., src/, app/, cmd/, packages/, services/) or code files are present to summarize.

What to do next (for maintainers)
- After adding your initial tech stack, update the sections above with exact commands to build, lint, test, and run a single test.
- Add a brief system-level architecture once modules/services/packages exist (focus on boundaries, major components, and how they interact).
- If you adopt AI assistant rules (CLAUDE.md, .cursor/rules/, .cursorrules, or .github/copilot-instructions.md), summarize key constraints and expectations here.
