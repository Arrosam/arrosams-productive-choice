# Arrosam’s Productive Choice

[简体中文](<README.zh.md>)

## Summary

A personal selection of [DeepSeek Harness (DSH)](<https://github.com/deepseek-ai/deepseek-harness>) plugins and Skills, curated by Arrosam for productive work. Browse selected plugin names, reusable agent instructions, and upstream documentation.

This repository is a curated directory, not an installable plugin bundle or an official DSH recommendation.

## Table of Contents

- [Selected plugins](#selected-plugins)
- [Selected Skills](#selected-skills)
- [Suggest a plugin or Skill](#suggest-a-plugin-or-skill)
- [Usage and limitations](#usage-and-limitations)

## Selected plugins

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

## Selected Skills

Arrosam explicitly selected the Skill below. Its individual selection reason has not been recorded. `@weibaohui/skills-management` is a plugin for managing Skills, not a Skill itself.

| Skill / upstream instructions | Use case | Before use |
| --- | --- | --- |
| [dsh-code-review](<https://github.com/deepseek-ai/deepseek-harness/blob/master/.agents/skills/dsh-code-review/SKILL.md>) | Review DeepSeek Harness pull requests against repository standards, prioritizing correctness, lifecycle, security, test evidence, and documentation consistency. | Requires a DSH source checkout, repository documentation, and related Skills; the guidance uses Git/GitHub and repository checks, not a universal review checklist. |

Verification on 2026-09-30 covered the local Skill instructions and existence of the upstream source. No standalone Skill version was identified, and no pull-request review was performed for this entry. The upstream repository declares MIT licensing. Follow the upstream instructions and retain access to their referenced files; this directory links the Skill rather than copying it.

## Suggest a plugin or Skill

Open an [issue](<https://github.com/Arrosam/arrosams-productive-choice/issues>) or a pull request with the item’s name and upstream link. See the [collection guidelines](<CONTRIBUTING.md>) for Skill entry details. Arrosam makes the final selection; a suggestion or local installation alone does not count as approval.

## Usage and limitations

Follow each item’s upstream documentation for installation and configuration. Distinguish plugins, profile bundles, libraries, and Skills; this directory does not provide a universal installation command or redistribute upstream code or Skill instructions.

A selection is not a security audit or a compatibility guarantee. Consult upstream documentation for current requirements, licenses, permissions, credentials, and possible costs before use. Upstream projects retain their own licenses.
