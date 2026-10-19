# ZT-DSP Suite

> This repository is named `.github` because GitHub requires that exact name for two
> things: the organisation profile page you are reading, and the default community
> health files that every repository here inherits unless it carries its own.
> It is not a scratch repository, and renaming it would switch both off.

Bilingual protocol specification and reference implementations.
Code is licensed AGPL-3.0-or-later. The specification is licensed CC BY-SA 4.0.

## Usage notice

Production: this protocol must not be used. Study: reading, reproduction and discussion are permitted.

Grounds:

1. The specification is unfinished. Its timestamp semantics change in the next revision.
2. No external security audit exists. No one has reviewed the cryptographic design.
3. The server role has no merged reference implementation.
4. Messages may vanish silently, with no error on either side.
5. Continuous integration on these repositories does not stay green.

Boundary for study: do not treat the published text as a build guide. The published text carries
open defects; implementing it hits known traps.

## 使用立场

生产环境：不得使用本协议。学习用途：可以阅读、可以复现、可以讨论。

依据：

1. 规范未完成。时间戳语义在下一版改变。
2. 没有外部安全审计。密码学设计无人复核。
3. 服务端角色没有已合并的参考实现。
4. 消息可静默消失，收发双方都不报错。
5. 这些子仓的持续集成不保持通过。

学习用途的边界：不得把公开文本当作施工图。公开文本带有 D1–D5 未修缺陷，照它实现会踩已知坑。

---

## Files

| File | What it is |
|---|---|
| [ZT-DSP-docs](https://github.com/ZT-DSP-Suite/ZT-DSP-docs) | the specification, published in both languages |
| [cn/spec](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/tree/main/cn/spec) · [en/spec](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/tree/main/en/spec) | protocol text |
| [CONFORMANCE-GUIDE](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/cn/CONFORMANCE-GUIDE.md) | how a conformance decision is reached |
| [DEV-GUIDE](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/cn/DEV-GUIDE.md) | build and verification commands |
| [LICENSING.md](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/LICENSING.md) | licence terms |
| [PUBLICATION-RECORD.md](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/PUBLICATION-RECORD.md) | publication time, commit and content hashes |
| [SECURITY.md](SECURITY.md) | how to report a vulnerability |
| [CONTRIBUTING.md](CONTRIBUTING.md) | how to contribute |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | conduct |

## Status

The specification is published. The reference implementations are not public.

---

# ZT-DSP 套件

> 本仓名为 `.github`，因为 GitHub 对两件事要求这个字面名字：你在读的这个组织首页，以及各仓未自带时继承的公共健康文件。它不是临时仓；改名会让这两项同时失效。

双语协议规范与参考实现。代码以 AGPL-3.0-or-later 授权，规范以 CC BY-SA 4.0 授权。

## 文件

| 文件 | 它是什么 |
|---|---|
| [ZT-DSP-docs](https://github.com/ZT-DSP-Suite/ZT-DSP-docs) | 规范，含中英两份 |
| [cn/spec](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/tree/main/cn/spec) · [en/spec](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/tree/main/en/spec) | 协议正文 |
| [符合性判定指南](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/cn/CONFORMANCE-GUIDE.md) | 一次实现是否合规怎么判 |
| [开发与验证指南](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/cn/DEV-GUIDE.md) | 构建与验证命令 |
| [LICENSING.md](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/LICENSING.md) | 许可条款 |
| [PUBLICATION-RECORD.md](https://github.com/ZT-DSP-Suite/ZT-DSP-docs/blob/main/PUBLICATION-RECORD.md) | 公开时刻、提交号与内容哈希 |
| [SECURITY.md](SECURITY.md) | 漏洞怎么报 |
| [CONTRIBUTING.md](CONTRIBUTING.md) | 贡献怎么做 |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | 行为准则 |

## 状态

规范已公开。参考实现尚未公开。
