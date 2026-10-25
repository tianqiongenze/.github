# 贡献指南 · Contributing

器识开源社区 / **QISHI Open Community** —「先器识，而后文艺」。
English readers: see [How to contribute](#how-to-contribute-in-english) below.

本文件是账号下所有仓库的默认贡献指南（GitHub 个人账号健康文件机制）。单个仓库若有自己的 `CONTRIBUTING.md`，以仓库内的为准。

## 15 分钟起步 · First 15 minutes

1. 打开 [社区中心仓库的议题板](https://github.com/tianqiongenze/community/labels/good%20first%20issue)，挑一个 `good first issue`，在议题下留言「认领 / I'll take this」。
2. Fork 目标仓库，建分支（`feat/…` `fix/…` `docs/…`）。
3. 提交信息沿用现有约定：前缀 `feat` / `fix` / `docs` / `test`，正文中文。
4. 提 PR。每个 `good first issue` 都有一名**具名兜底人**（议题正文里写明），他负责在 7 天内给你第一次完整评审。

## 我们接受什么形式的贡献

代码不是唯一入口，以下都算贡献，都进致谢区：

| 类型 | 例子 | 需要写代码吗 |
| --- | --- | --- |
| 报问题 | 描述场景、已有数据、期望产出 | 否 |
| 文档与课件 | 按「七件套」模板补一个任务单元 | 否 |
| 领域口径 | 农艺标注口径、故障退化标签定义、协议报文样例 | 否 |
| 评测与复现 | 给出可复现台架、失败样例清单、评测脚本 | 少量 |
| 翻译与本地化 | 繁中术语校对、英文文案、对比度审计 | 否 |
| 教学与布道 | 用这些课程开课并回报使用问题 | 否 |

## 角色阶梯 · Contributor ladder

见 [GOVERNANCE.md](https://github.com/tianqiongenze/community/blob/main/GOVERNANCE.md)。简版：

`使用者 → 问题报告者 → 贡献者（首个被合并的 PR）→ 评审者 → 维护者（某轨道/仓库）`

晋升看**持续**而非单次：维护者一级要求至少 6 个月的可验证贡献记录。

## 提 PR 之前

- 一个 PR 只做一件事；超过约 400 行diff 请先开议题讨论。
- 教学资产类仓库：请附**可运行**的代码或可打开的课件，不要只交提纲。
- 工业/协议类仓库：请附报文样例或数据样例，否则无法验收。
- 不要提交真实生产数据、企业内网地址、学员姓名与成绩。涉及企业场景的内容以脱敏样例代替。

## 行为准则

参与者需遵守 [Code of Conduct](./CODE_OF_CONDUCT.md)。争议处理走 SECURITY/SUPPORT 里写的联系方式。

## How to contribute (in English)

1. Pick an issue labelled `good first issue` in the [community hub](https://github.com/tianqiongenze/community). Each one names a human reviewer who commits to a full review within 7 days.
2. Fork, branch (`feat/…`, `fix/…`, `docs/…`), open a pull request. One concern per PR; anything over ~400 changed lines should be discussed in an issue first.
3. Contributions are not code-only: issue reports, courseware units, domain label taxonomies, replayable protocol captures, translations, and teaching reports all count and are credited.

Course and platform repositories carry Chinese names and Chinese documentation on purpose — they are used in Chinese vocational classrooms. Do not machine-translate them; propose a separate English overview instead.
