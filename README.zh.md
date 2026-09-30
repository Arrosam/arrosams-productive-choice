# Arrosam’s Productive Choice

[English](<README.md>)

## 概述

由 Arrosam 挑选的 [DeepSeek Harness（DSH）](<https://github.com/deepseek-ai/deepseek-harness>) 插件与 Skills 目录，面向日常高效工作。在这里查看精选工具与可复用的智能体指令、使用场景，以及上游文档。

本仓库是精选目录，不是可安装的插件组合，也不代表 DSH 官方推荐。

## 目录

- [精选插件](#精选插件)
- [精选 Skills](#精选-skills)
- [推荐插件或 Skill](#推荐插件或-skill)
- [使用与限制](#使用与限制)

## 精选插件

以下五个条目均由 Arrosam 明确选择收录。各条目的具体选择理由尚未记录；使用场景概括自已安装包的描述，不代表个人使用评价。

| 插件 / 上游文档 | 使用场景 | 本地观察到的安装版本 | 使用前注意 |
| --- | --- | --- | --- |
| [dsh-plugin-subscriptions](<https://github.com/V1ki/dsh-plugin-subscriptions#readme>) | 将 ChatGPT/Codex、Claude、Grok、GitHub Copilot 和 Google Antigravity 订阅接入 DSH，作为模型提供方。 | `0.9.6` | 查看各提供方的账号要求、订阅条款、凭据和对外数据处理方式。 |
| [@weibaohui/skills-management](<https://github.com/weibaohui/skills-management#readme>) | 管理本机 coding agent 的 Skills，浏览和安装技能市场内容，并控制模型可见性。 | `0.6.11` | 在向智能体开放指令前审查每个 Skill；收录管理器不代表认可市场中的所有 Skills。 |
| [dsh-rewind-plugin](<https://github.com/SiriLee/dsh-rewind#readme>) | 在同一窗口回退对话，并可选择还原工作区文件。 | `0.15.0` | 对重要的工作区改动使用回退前，先了解文件还原行为。 |
| [dsh-notification](<https://github.com/nishit130/dsh-notification#readme>) | 在一轮任务完成、出错或需要审批时发送桌面及 Webhook 通知。 | `0.1.2` | 检查桌面权限和 Webhook 目的地，了解哪些通知数据会离开本机。 |
| [dshmarket](<https://github.com/dsh-market/dsh-market#readme>) | 在 DSH 内浏览、搜索和安装社区插件。 | `1.66.6` | 单独审查每个插件的来源和权限；收录市场不代表认可其全部目录。 |

### 验证范围

本地安装于 2026-09-30 检查，DSH 版本为 `0.2.0-rc.2`，profile 为 `web`。这五个包均出现在 profile 的依赖和 bundle 清单中，各自声明通过 bundle 补丁挂载插件。表格记录观察到的版本，不代表版本要求或兼容性保证。

验证仅覆盖已安装包的元数据和 profile 配置，未逐项进行功能测试或安全审计。五个已安装包均声明使用 MIT 许可证；复用前请查看上游许可证正文。具体权限要求和潜在服务费用尚未独立验证。

## 精选 Skills

以下 Skill 由 Arrosam 明确选择收录，具体选择理由尚未记录。`@weibaohui/skills-management` 是管理 Skills 的插件，本身不是 Skill。

| Skill / 上游指令 | 使用场景 | 使用前注意 |
| --- | --- | --- |
| [dsh-code-review](<https://github.com/deepseek-ai/deepseek-harness/blob/master/.agents/skills/dsh-code-review/SKILL.md>) | 按仓库规范审查 DeepSeek Harness 的 Pull Request，优先检查正确性、生命周期、安全、测试证据和文档一致性。 | 需要 DSH 源码仓库、仓库文档和相关 Skills；指引涉及 Git/GitHub 与仓库检查，不是适用于所有项目的审查清单。 |

2026-09-30 的验证覆盖本地 Skill 指令和上游来源的存在性。未发现独立的 Skill 版本号，也未为此条目执行实际 Pull Request 审查。上游仓库声明使用 MIT 许可证。使用时遵循上游指令，并保留对其引用文件的访问；本目录仅链接该 Skill，不复制其内容。

## 推荐插件或 Skill

通过 [Issue](<https://github.com/Arrosam/arrosams-productive-choice/issues>) 或 Pull Request 提供条目的上游链接、使用场景，以及已知的前提条件或风险。条目所需信息见[收录规范](<CONTRIBUTING.zh.md>)。最终由 Arrosam 决定是否收录；推荐或本地已安装本身不等于认可。

## 使用与限制

安装与配置请遵循各条目的上游文档。需要区分插件、配置组合（profile bundle）、库和 Skills；本目录不提供统一安装命令，也不重新分发上游代码或 Skill 指令。

收录不等于安全审计，也不保证兼容所有 DSH 版本。使用前请查看验证记录、上游许可证、权限、凭据要求及潜在费用。上游项目保留各自的许可证。
