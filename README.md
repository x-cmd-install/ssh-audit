# ssh-audit

[中文版本](./README.cn.md)

SSH server & client security auditing (banner, key exchange, encryption, mac, compression, compatibility, security, etc)

![ssh-audit](https://repo.x-cmd.io/ssh-audit.svg)

## Install

```sh
x install ssh-audit
```

## Code insight

Total: **14,598** lines of code across **87** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Python | 8,497 | 657 | 1,649 | 49 |
| Json | 5,077 | 0 | 0 | 31 |
| Sh | 685 | 260 | 235 | 5 |
| Batch | 121 | 1 | 9 | 1 |
| Ini | 113 | 7 | 10 | 1 |

## OpenSSF Scorecard

Overall score: **4.2 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Code-Review** (0/10) — Found 1/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## Source

- **Upstream**: <https://github.com/jtesta/ssh-audit>
- **License**: MIT

## Release

- **Latest**: `v3.9.0` (2026-07-04)
- **Last commit**: 2026-07-09
- **Assets in release**: 7

## Popularity

- **Stars**: 4,298 · **Forks**: 226 · **Open issues**: 281 · **Contributors**: 33

## Totals (cumulative)

- **Releases**: 14 · **Merged PRs**: 52 · **Open PRs**: 2 · **Closed issues**: 244 · **Open issues**: 37 · **Commits**: 723

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 2 | 0 |
| last60d | 2026-07-12 | 0 | 0 | 1 | 0 | 5 | 0 |
| 90d | 2026-06-12 | 1 | 0 | 1 | 5 | 11 | 16 |
| last180d | 2026-03-14 | 1 | 1 | 1 | 9 | 12 | 23 |
| 360d | 2025-09-15 | 1 | 1 | 1 | 10 | 15 | 23 |
| last720d | 2024-09-20 | 2 | 4 | 1 | 32 | 25 | 79 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [jtesta_2020-2025.asc](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/jtesta_2020-2025.asc) | 3.8 KiB | `other` |
| [jtesta_2026-2029.asc](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/jtesta_2026-2029.asc) | 681 B | `other` |
| [jtesta_2026-2029.asc.sig](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/jtesta_2026-2029.asc.sig) | 566 B | `other` |
| [ssh-audit.exe](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/ssh-audit.exe) | 9.3 MiB | `other` |
| [ssh-audit.exe.sig](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/ssh-audit.exe.sig) | 119 B | `other` |
| [v3.9.0.tar.gz](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/v3.9.0.tar.gz) | 178.3 KiB | `native/unknown` |
| [v3.9.0.tar.gz.sig](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/v3.9.0.tar.gz.sig) | 119 B | `other` |

## Distribution status

Reported by **106** distros on [repology.org](https://repology.org/project/ssh-audit). **20** are ✅ on the latest upstream release, **79** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `3.3.0` | ⚠️ outdated |
| Debian 14 | `3.3.0` | ⚠️ outdated |
| Debian 13 | `3.3.0` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.3.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.1.0` | ⚠️ outdated |
| Arch | `3.9.0` | ✅ latest |
| Homebrew | `3.9.0` | ✅ latest |
| Fedora rawhide | `3.3.0` | ⚠️ outdated |
| Nix unstable | `3.9.0` | ✅ latest |
| Void | `3.9.0` | ✅ latest |
| Alpine edge | `3.9.0` | ✅ latest |
| openSUSE Tumbleweed | `3.9.0` | ✅ latest |

## Improve this data

Install metadata for ssh-audit lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `ssh-audit` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/ssh-audit.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:34:20Z._
