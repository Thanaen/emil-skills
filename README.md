# emil-skills

Claude Code plugin marketplace that tracks [emilkowalski/skill](https://github.com/emilkowalski/skill) directly, so the skills stay up to date as Emil publishes them.

```bash
claude plugin marketplace add Thanaen/emil-skills
claude plugin install emil@emil-skills --scope user
```

Then enable auto-update in `/plugin` → Marketplaces → emil-skills.

Skills are invoked as `/emil:<skill>`, e.g. `/emil:animate`.
