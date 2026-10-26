# ZT-DSP Suite

> This repository is named `.github` because GitHub requires that exact name for two
> things: the organisation profile page you are reading, and the default community
> health files that every repository here inherits unless it carries its own.
> It is not a scratch repository, and renaming it would switch both off.

Bilingual protocol specification and reference implementations.
Code is licensed AGPL-3.0-or-later. The specification is licensed CC BY-SA 4.0.

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

The specification is published. No release exists. Repository code is for testing and does not constitute a release.
No browser or messaging software currently supports this protocol.
No public deployment exists.
The client and server roles have reference implementations, and nothing is
released.
The initial developers, SCAL-ROAM and NullMaverick, do not use it for
communication either.

## Update commitment

**Guarantee: 26 update weeks.**

An update week runs Monday to Sunday, UTC+8. It counts when at least one commit lands on a default branch of a repository in this organization and changes protocol text, implementation behavior, tests, or security posture. A week with only formatting or typo changes does not count.

Scope: default branches of all repositories in this organization.

Start: the week this section merges. End: the 26th update week.

Four weeks before the end, this page states a renewal or a stop date.

This commitment covers updates. It does not cover support, response time, or feature requests.

Verification: run `git log --since=<start> --until=<end> --date=short` on each repository. Every update week lists at least one qualifying commit.

## Collaboration window

Issues and pull requests are submitted Monday to Friday, UTC+8. Review and merge are handled Friday to Sunday, UTC+8.

The window is a convention, not a service promise.

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

规范已公开。无发行版。仓内代码仅作测试，不构成发布。
目前没有任何浏览器或通讯软件支持本协议。
没有任何公开部署。
客户端与服务端角色都有参考实现，且没有任何发行版。
初始开发者 SCAL-ROAM 与 NullMaverick 也没有在用本协议通信。

## 持续更新承诺

**保证：26 个更新周。**

更新周按 UTC+8 的周一至周日计。一周内至少一个提交进入本组织任一仓的默认分支，且改动协议正文、实现行为、测试或安全姿态，记为一个更新周。只改格式或错别字的一周不计。

范围：本组织全部仓的默认分支。

起点：本节合并所在周。终点：第 26 个更新周。

终点前 4 周，本页公布续期或终止日期。

本承诺只覆盖更新。不覆盖支持、响应时间与功能请求。

复核：在每个仓跑 `git log --since=<起始日> --until=<结束日> --date=short`。每个更新周至少列出一条合格提交。

## 协作窗口

议题与 PR 在周一至周五（UTC+8）提交。评审与合并在周五至周日（UTC+8）处理。

窗口是惯例，不是服务承诺。
