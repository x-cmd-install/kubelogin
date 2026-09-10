# kubelogin

[中文版本](./README.cn.md)

A Kubernetes credential (exec) plugin implementing azure authentication

![kubelogin](https://repo.x-cmd.io/kubelogin.svg)

## Install

```sh
x install kubelogin
```

## Source

- **Upstream**: <https://github.com/Azure/kubelogin>
- **Homepage**: <https://azure.github.io/kubelogin/>
- **License**: MIT

## Release

- **Latest**: `v0.2.19` (2026-06-23)
- **Last commit**: 2026-09-01
- **Assets in release**: 17

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [kubelogin-darwin-amd64.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-darwin-amd64.zip) | 28.4 MiB | `native/darwin/x64` |
| [kubelogin-darwin-amd64.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-darwin-amd64.zip.sha256) | 93 B | `native/darwin/x64` |
| [kubelogin-darwin-arm64.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-darwin-arm64.zip) | 25.8 MiB | `native/darwin/arm64` |
| [kubelogin-darwin-arm64.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-darwin-arm64.zip.sha256) | 93 B | `native/darwin/arm64` |
| [kubelogin-linux-amd64.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-linux-amd64.zip) | 23.3 MiB | `native/linux/x64` |
| [kubelogin-linux-amd64.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-linux-amd64.zip.sha256) | 92 B | `native/linux/x64` |
| [kubelogin-linux-arm64.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-linux-arm64.zip) | 21.1 MiB | `native/linux/arm64` |
| [kubelogin-linux-arm64.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-linux-arm64.zip.sha256) | 92 B | `native/linux/arm64` |
| [kubelogin-linux-armv7.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-linux-armv7.zip) | 21.6 MiB | `native/linux/arm` |
| [kubelogin-linux-armv7.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-linux-armv7.zip.sha256) | 92 B | `native/linux/arm` |
| [kubelogin-version.txt](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-version.txt) | 7 B | `other` |
| [kubelogin-win-amd64.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-win-amd64.zip) | 23.6 MiB | `other` |
| [kubelogin-win-amd64.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-win-amd64.zip.sha256) | 90 B | `other` |
| [kubelogin-win-arm64.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-win-arm64.zip) | 21.2 MiB | `other` |
| [kubelogin-win-arm64.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin-win-arm64.zip.sha256) | 90 B | `other` |
| [kubelogin.zip](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin.zip) | 165.0 MiB | `other` |
| [kubelogin.zip.sha256](https://github.com/Azure/kubelogin/releases/download/v0.2.19/kubelogin.zip.sha256) | 80 B | `other` |

## Popularity

- **Stars**: 584 · **Forks**: 127 · **Open issues**: 221 · **Contributors**: 2,949

## Totals (cumulative)

- **Releases**: 63 · **Merged PRs**: 340 · **Open PRs**: 15 · **Closed issues**: 193 · **Open issues**: 28 · **Commits**: 349

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 2 | 8 | 0 | 1 | 2 |
| 90d | 2026-06-12 | 1 | 15 | 11 | 1 | 1 | 16 |
| 360d | 2025-09-15 | 8 | 56 | 13 | 14 | 6 | 58 |

## Code size

Total: **13,190** lines of code across **117** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 10,700 | 669 | 1,434 | 102 |
| Yaml | 2,362 | 0 | 0 | 10 |
| Makefile | 81 | 3 | 18 | 2 |
| Sh | 26 | 6 | 10 | 2 |
| Toml | 12 | 0 | 2 | 1 |

## OpenSSF Scorecard

Overall score: **8.2 / 10**

Lowest-scoring checks:

- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: githubv4.Query: Resource not accessible by integrati…
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## Improve this data

Install metadata for kubelogin lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `kubelogin` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/kubelogin.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T16:20:32Z._
