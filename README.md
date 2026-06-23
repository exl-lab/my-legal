# My Legal

A small suite of AI tools for lawyers. Each tool is a self-contained skill that works two ways:
**paste it into any AI chat** (even a free one, no install needed), or **install it into Claude Code**.
Each tool's own folder has a README with the details.

| Folder | Tool | What it does |
|--------|------|--------------|
| `my-legal-playbook/` | **My Legal Playbook** | Interview-builds a numbered playbook for a recurring task, runs a document through it one item at a time, and has a separate agent double-check the result. |
| `my-legal-hypo/` | **My Legal Hypo** | Teaches a legal topic by retrieval practice: poses a hard question at the edge of what you know, holds the answer until you try, then teaches the gap your attempt exposes. Installed, it remembers your progress across sessions. |

## Install (Claude Code)

Copy any tool's folder into your Claude skills directory, keeping the folder name. For example, for My Legal Hypo:

    cp -r my-legal-hypo ~/.claude/skills/my-legal-hypo

Then run it from Claude Code, for example `/my-legal-hypo`.

## No install: copy-paste prompts

Each tool also ships as a plain copy-paste prompt that works in any chatbot, even a free one. See
the tool's own README.

## License
MIT (see [LICENSE](LICENSE)). Copyright (c) 2026 Eric Xiyu Li.

