# saas-tech-writer

An AI skill for software and SaaS technical writers. It helps you correct grammar, turn rough drafts into polished first drafts, apply Microsoft Writing Style Guide principles, and improve how easily users find and use your docs.

## What it does

- **Edit:** Fixes grammar, clarity, and style, and tells you what changed.
- **Draft:** Turns notes, tickets, or rough drafts into structured docs.
- **Review:** Audits a doc and returns a prioritized issues table.
- **Improve:** Suggests discoverability, usage, support deflection, and measurement ideas.

## Supported doc types

- Release notes
- Defect fix documentation (resolved and known issues)
- Installation and setup guides
- Feature documentation
- Procedures and how-tos
- Troubleshooting topics

## Install

### Option 1: skills.sh (works with Claude Code, Cursor, Copilot, Codex, and other agents)

```bash
npx skills add <your-github-username>/saas-tech-writer
```

### Option 2: Claude Code (manual)

```bash
# Personal (all projects)
git clone https://github.com/<your-github-username>/saas-tech-writer.git ~/.claude/skills/saas-tech-writer

# Or project-level
git clone https://github.com/<your-github-username>/saas-tech-writer.git .claude/skills/saas-tech-writer
```

### Option 3: Other AI tools (ChatGPT, Gemini, Copilot, etc.)

Copy the contents of `SKILL.md` into your custom instructions, project instructions, or system prompt. Attach the files in `references/` as knowledge files if the tool supports it.

## Use it

Just ask in plain language:

- "Fix the grammar and apply Microsoft style to this paragraph."
- "Write release notes for version 4.2 from these Jira tickets."
- "Create a defect fix document from this bug description."
- "Draft an installation guide for our Linux agent."
- "Review this procedure and list the style issues."
- "How can I make this help topic easier to find?"

## Customize

- Add your company style guide to `references/` and mention it in `SKILL.md`.
- Add your own templates to `references/templates.md`.
- Keep `SKILL.md` short. Put detail in `references/`.

## Repository layout

```
saas-tech-writer/
├── SKILL.md
├── README.md
└── references/
    ├── microsoft-style-checklist.md
    ├── templates.md
    └── discoverability-and-usage.md
```

## Notes

- The skill summarizes style principles in original wording. It is not affiliated with or endorsed by Microsoft.
- Always verify product facts, UI labels, and versions before publishing.

## License

MIT. Contributions welcome. Open an issue or pull request.
