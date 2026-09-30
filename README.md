# Arrosam’s Productive Choice

[简体中文](<README.zh.md>)

## Summary

A personal selection of [DeepSeek Harness (DSH)](<https://github.com/deepseek-ai/deepseek-harness>) plugins and Skills, curated by Arrosam for productive work. Browse selected tools and reusable agent instructions, their use cases, and upstream documentation.

This repository is a curated directory, not an installable plugin bundle or an official DSH recommendation.

## Table of Contents

- [Selected plugins](#selected-plugins)
- [Selected Skills](#selected-skills)
- [Suggest a plugin or Skill](#suggest-a-plugin-or-skill)
- [Usage and limitations](#usage-and-limitations)

## Selected plugins

Arrosam explicitly selected all five entries below. Their individual selection reasons have not been recorded; the use cases summarize installed package descriptions, not personal testimonials.

| Plugin / upstream documentation | Use case | Observed installed version | Before use |
| --- | --- | --- | --- |
| [dsh-plugin-subscriptions](<https://github.com/V1ki/dsh-plugin-subscriptions#readme>) | Connect ChatGPT/Codex, Claude, Grok, GitHub Copilot, and Google Antigravity subscriptions as DSH model providers. | `0.9.6` | Review provider account requirements, subscription terms, credentials, and external data handling. |
| [@weibaohui/skills-management](<https://github.com/weibaohui/skills-management#readme>) | Manage local coding-agent Skills, browse and install market Skills, and control model visibility. | `0.6.11` | Review each Skill before exposing its instructions to an agent; selecting this manager does not endorse every market Skill. |
| [dsh-rewind-plugin](<https://github.com/SiriLee/dsh-rewind#readme>) | Rewind a conversation in the same window and optionally restore workspace files. | `0.15.0` | Review file-restoration behavior before using it on important workspace changes. |
| [dsh-notification](<https://github.com/nishit130/dsh-notification#readme>) | Send desktop and webhook notifications when a turn finishes, fails, or needs approval. | `0.1.2` | Check desktop permissions and webhook destinations; review what notification data leaves the machine. |
| [dshmarket](<https://github.com/dsh-market/dsh-market#readme>) | Browse, search, and install community plugins inside DSH. | `1.66.6` | Review each plugin’s source and permissions separately; selecting the market does not endorse its entire catalog. |

### Verification scope

The local installation was inspected on 2026-09-30 with DSH `0.2.0-rc.2`, profile `web`. All five packages were present in the profile’s dependencies and bundle list; each declares a bundle patch that mounts its plugin. The table records observed versions, not required versions or compatibility guarantees.

Verification covered installed package metadata and profile configuration only. It did not include per-plugin functional tests or security audits. All five installed packages declare MIT licensing; consult their upstream license text before reuse. Detailed permission requirements and potential service costs have not been independently verified.

## Selected Skills

Arrosam explicitly selected the Skill below. Its individual selection reason has not been recorded. `@weibaohui/skills-management` is a plugin for managing Skills, not a Skill itself.

| Skill / upstream instructions | Use case | Before use |
| --- | --- | --- |
| [dsh-code-review](<https://github.com/deepseek-ai/deepseek-harness/blob/master/.agents/skills/dsh-code-review/SKILL.md>) | Review DeepSeek Harness pull requests against repository standards, prioritizing correctness, lifecycle, security, test evidence, and documentation consistency. | Requires a DSH source checkout, repository documentation, and related Skills; the guidance uses Git/GitHub and repository checks, not a universal review checklist. |

Verification on 2026-09-30 covered the local Skill instructions and existence of the upstream source. No standalone Skill version was identified, and no pull-request review was performed for this entry. The upstream repository declares MIT licensing. Follow the upstream instructions and retain access to their referenced files; this directory links the Skill rather than copying it.

## Suggest a plugin or Skill

Open an [issue](<https://github.com/Arrosam/arrosams-productive-choice/issues>) or a pull request with the item’s upstream link, intended use case, and any known prerequisites or risks. See the [collection guidelines](<CONTRIBUTING.md>) for the information required for an entry. Arrosam makes the final selection; a suggestion or local installation alone does not count as approval.

## Usage and limitations

Follow each item’s upstream documentation for installation and configuration. Distinguish plugins, profile bundles, libraries, and Skills; this directory does not provide a universal installation command or redistribute upstream code or Skill instructions.

A selection is not a security audit or a guarantee of compatibility with every DSH version. Check verification details, upstream licenses, permissions, credential requirements, and possible costs before use. Upstream projects retain their own licenses.
