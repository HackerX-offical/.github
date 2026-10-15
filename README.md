# HackerX-official `.github`

Organization profile and shared standards for [HackerX-official](https://github.com/HackerX-official).

## Why this exists

GitHub org profiles and license text should have a single source of truth. This repository hosts the public org page, HackerX License v1.0, and the conventions every member repo follows.

## Quick start

1. Edit [`profile/README.md`](./profile/README.md) to update the org landing page.
2. Change [`ORG_STANDARDS.md`](./ORG_STANDARDS.md) when adding a new required file or CI check.
3. Push to `main` — the `standards` workflow validates LICENSE, NOTICE, ARCHITECTURE, and README artifacts.

| Artifact | Purpose |
| --- | --- |
| [`profile/README.md`](./profile/README.md) | Public org landing page on GitHub |
| [`ORG_STANDARDS.md`](./ORG_STANDARDS.md) | Required files, license, and CI conventions |
| [`ARCHITECTURE.md`](./ARCHITECTURE.md) | How this meta-repo fits the org |
| [`LICENSE`](./LICENSE) / [`NOTICE`](./NOTICE) | HackerX License v1.0 source of truth |
| [`SECURITY.md`](./SECURITY.md) | Coordinated disclosure template |

Member repositories mirror these conventions locally; they do not depend on this repo as a submodule.

## License

HackerX License v1.0 — see [LICENSE](./LICENSE) and [NOTICE](./NOTICE).
