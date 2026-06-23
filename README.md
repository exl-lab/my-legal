# My Legal

A small suite of AI tools for lawyers. Each tool is a self-contained skill: copy the one you
want into Claude Code and run it. Most also work as a copy-paste prompt in any AI chat,
no install needed.

| Folder | Tool | What it does | Where it runs | Status |
|--------|------|--------------|---------------|--------|
| `my-legal-playbook/` | **My Legal Playbook** | Interview-builds a numbered playbook for a recurring task, runs a document through it one item at a time, and has a separate agent double-check the result. | Any AI chat (copy-paste) **or** Claude Code | **Ready** |
| `my-legal-hypo/` | **My Legal Hypo** | Teaches a legal topic by retrieval practice: poses a hard question at the edge of what you know, holds the answer until you try, then teaches the gap your attempt exposes. Installed, it remembers your progress across sessions. | Any AI chat (copy-paste) **or** Claude Code | **Ready** |

## Install (Claude Code)

Copy the folder for the tool you want into your Claude skills directory, keeping the folder name:

    cp -r my-legal-playbook ~/.claude/skills/my-legal-playbook

Then run it from Claude Code, for example `/my-legal-playbook`. Each tool's own
folder has a README with the details.

## No install: copy-paste prompts

My Legal Playbook and My Legal Hypo each also ship as a plain copy-paste prompt that works in any
chatbot, even a free one. See each tool's own README.

## License
MIT (see [LICENSE](LICENSE)). Copyright (c) 2026 Eric Xiyu Li.

