# ssh-audit

[English version](./README.md)

SSH server & client security auditing (banner, key exchange, encryption, mac, compression, compatibility, security, etc)

![ssh-audit](https://repo.x-cmd.io/ssh-audit.svg?lang=zh)

## 安装

```sh
x install ssh-audit
```

## 代码洞察

合计: **14,598** 行代码（覆盖前 5 种语言、共 **87** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 8,497 | 657 | 1,649 | 49 |
| Json | 5,077 | 0 | 0 | 31 |
| Sh | 685 | 260 | 235 | 5 |
| Batch | 121 | 1 | 9 | 1 |
| Ini | 113 | 7 | 10 | 1 |

## OpenSSF Scorecard 评分

总评分: **4.2 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Code-Review** (0/10) — Found 1/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/jtesta/ssh-audit>
- **许可证**: MIT

## 发布

- **最新版本**: `v3.9.0` (2026-07-04)
- **最近提交**: 2026-07-09
- **Release 含资产**: 7 个

## 流行度

- **Star**: 4,298 · **Fork**: 226 · **开放 issue**: 281 · **贡献者**: 33

## 累计统计

- **发布数**: 14 · **已合并 PR**: 52 · **开放 PR**: 2 · **已关闭 issue**: 244 · **开放 issue**: 37 · **提交数**: 723

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 2 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 1 | 0 | 4 | 0 |
| 90d | 2026-06-13 | 1 | 0 | 1 | 4 | 11 | 0 |
| last180d | 2026-03-15 | 1 | 1 | 1 | 9 | 12 | 0 |
| 360d | 2025-09-16 | 1 | 1 | 1 | 10 | 15 | 0 |
| last720d | 2024-09-21 | 2 | 4 | 1 | 32 | 25 | 79 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [jtesta_2020-2025.asc](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/jtesta_2020-2025.asc) | 3.8 KiB | `other` |
| [jtesta_2026-2029.asc](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/jtesta_2026-2029.asc) | 681 B | `other` |
| [jtesta_2026-2029.asc.sig](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/jtesta_2026-2029.asc.sig) | 566 B | `other` |
| [ssh-audit.exe](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/ssh-audit.exe) | 9.3 MiB | `other` |
| [ssh-audit.exe.sig](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/ssh-audit.exe.sig) | 119 B | `other` |
| [v3.9.0.tar.gz](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/v3.9.0.tar.gz) | 178.3 KiB | `native/unknown` |
| [v3.9.0.tar.gz.sig](https://github.com/jtesta/ssh-audit/releases/download/v3.9.0/v3.9.0.tar.gz.sig) | 119 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/ssh-audit) 上共有 **106** 个发行版报告此项目。**20** 个 ✅ 已是最新上游版本，**79** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
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

## 改进这些数据

ssh-audit 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `ssh-audit` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/ssh-audit.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T18:43:47Z._
