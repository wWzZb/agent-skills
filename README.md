# Agent Skills

A growing index of reusable Agent Skills that I build and maintain for AI-assisted workflows.

这是我持续积累的 Agent Skill 合集。每个 Skill 保持独立仓库，方便单独安装、维护和迭代；这个仓库负责提供统一入口。

## Skills

| Skill | What it does | Works with | Source & install |
|---|---|---|---|
| **Conversation Review** | Turns conversations and work traces into scoped, evidence-based retrospectives in Markdown or self-contained HTML. | Codex, Claude Code, Cursor, and other Agent Skills-compatible tools | [Source](https://github.com/wWzZb/codex-conversation-review-skill) · `npx skills add wWzZb/codex-conversation-review-skill` |
| **LeetCode Hot 100 Coach** | Guides Python beginners through LeetCode Hot 100 with worked examples, progressively fewer hints, and a local dashboard for practice and review. | Codex with Python 3 on macOS or Linux | [Source](https://github.com/wWzZb/leetcode-hot100-coach) · [Install guide](https://github.com/wWzZb/leetcode-hot100-coach#安装-skill) |
| **UI State Board** | Renders real frontend code in an interactive review board where you can browse page states, try interactions, and copy element IDs for feedback. | Codex | [Source](https://github.com/wWzZb/ui-state-board) · `npx skills add wWzZb/ui-state-board` · [Live demo](https://wwzzb.github.io/ui-state-board/board/) |

## Quick Start

Install Conversation Review with the Skills CLI:

```bash
npx skills add wWzZb/codex-conversation-review-skill
```

Install it globally for Codex, Claude Code, and Cursor:

```bash
npx skills add wWzZb/codex-conversation-review-skill \
  --agent codex claude-code cursor \
  --global
```

## How This Collection Is Organized

- Each Skill lives in its own repository and has its own documentation, examples, tests, and release history.
- This repository stays lightweight and acts as the discoverable index.
- New Skills will be added here as they become ready for public use.

## License

This index repository is licensed under the [MIT License](LICENSE). Each linked Skill repository contains its own license and usage terms.
