# Arrosam’s Productive Choice

[English](<README.md>)

## 概述

由 Arrosam 挑选的 [DeepSeek Harness（DSH）](<https://github.com/deepseek-ai/deepseek-harness>) 插件与 Skills 目录，面向日常高效工作。在这里查看精选插件名、可复用的智能体指令，以及上游文档。

本仓库是精选目录，不是可安装的插件组合，也不代表 DSH 官方推荐。

## 目录

- [精选插件](#精选插件)
- [精选 Skills](#精选-skills)
- [推荐插件或 Skill](#推荐插件或-skill)
- [使用与限制](#使用与限制)

## 精选插件

- [dsh-plugin-subscriptions](<https://github.com/V1ki/dsh-plugin-subscriptions#readme>)
- [@weibaohui/skills-management](<https://github.com/weibaohui/skills-management#readme>)
- [dsh-rewind-plugin](<https://github.com/SiriLee/dsh-rewind#readme>)
- [dsh-notification](<https://github.com/nishit130/dsh-notification#readme>)
- [dshmarket](<https://github.com/dsh-market/dsh-market#readme>)
- [@linxin666/dsh-client-ui-git-graph](<https://github.com/zhu1090093659/dsh-web#readme>)
- [@roarpeng/graphflow](<https://github.com/Roarpeng/GraphFlow#readme>)
- [@openviking/dsh-memory-plugin](<https://github.com/volcengine/OpenViking/blob/main/examples/dsh-memory-plugin/README.md>)
- [@michengai/dsh-btw](<https://github.com/MichengAI/dsh-btw#readme>)
- [@michengai/dsh-code-review](<https://github.com/MichengAI/dsh-code-review#readme>)
- [dsh-diff-approval](<https://github.com/9087/dsh-diff-approval#readme>)
- [dsh-improve-prompt](<https://github.com/hoyyang/dsh-improve-prompt#readme>)

## 精选 Skills

以下 Skill 由 Arrosam 明确选择收录，具体选择理由尚未记录。`@weibaohui/skills-management` 是管理 Skills 的插件，本身不是 Skill。

| Skill / 上游指令 | 使用场景 | 使用前注意 |
| --- | --- | --- |
| [dsh-code-review](<https://github.com/deepseek-ai/deepseek-harness/blob/master/.agents/skills/dsh-code-review/SKILL.md>) | 按仓库规范审查 DeepSeek Harness 的 Pull Request，优先检查正确性、生命周期、安全、测试证据和文档一致性。 | 需要 DSH 源码仓库、仓库文档和相关 Skills；指引涉及 Git/GitHub 与仓库检查，不是适用于所有项目的审查清单。 |

2026-09-30 的验证覆盖本地 Skill 指令和上游来源的存在性。未发现独立的 Skill 版本号，也未为此条目执行实际 Pull Request 审查。上游仓库声明使用 MIT 许可证。使用时遵循上游指令，并保留对其引用文件的访问；本目录仅链接该 Skill，不复制其内容。

## 推荐插件或 Skill

通过 [Issue](<https://github.com/Arrosam/arrosams-productive-choice/issues>) 或 Pull Request 提供条目名称和上游链接。Skill 条目的详细要求见[收录规范](<CONTRIBUTING.zh.md>)。最终由 Arrosam 决定是否收录；推荐或本地已安装本身不等于认可。

## 使用与限制

安装与配置请遵循各条目的上游文档。需要区分插件、配置组合（profile bundle）、库和 Skills；本目录不提供统一安装命令，也不重新分发上游代码或 Skill 指令。

收录不等于安全审计或兼容性保证。使用前请查看上游文档中的当前要求、许可证、权限、凭据及潜在费用。上游项目保留各自的许可证。
