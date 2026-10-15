# HackerX organization standards

All public repositories in **HackerX-official** should include:

| Artifact | Purpose |
| --- | --- |
| [LICENSE](https://github.com/HackerX-official/.github/blob/main/LICENSE) | HackerX License v1.0 |
| [NOTICE](https://github.com/HackerX-official/.github/blob/main/NOTICE) | Attribution for distributions |
| `SECURITY.md` | Vulnerability reporting |
| `README.md` | Install, usage, ethics, license section |
| `ARCHITECTURE.md` | Required for `hx-*` security CLIs |

Node/TypeScript projects should use:

- `.editorconfig`, Prettier (`format` / `format:check`)
- `.github/workflows/ci.yml` — build, test, format check

Apply tooling from the internal `org-standards` workspace (maintainers) or copy files from any `hx-*` repository.
