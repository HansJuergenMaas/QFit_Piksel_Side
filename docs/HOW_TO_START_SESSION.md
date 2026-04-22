# How to Start a New QFit Website Session

> Follow these steps at the beginning of every new working session.

---

## Quick Start (30 seconds)

```bash
cd ~/Documents/Piksel/qfit-website
git pull
claude
```

Then say to Claude Code:
```
Please read all documents in the docs/ folder and tell me where we stand.
```

Claude Code will respond with:
- Summary of current project status
- What was done last session
- Suggested next step

---

## If you want to plan first (in claude.ai)

1. Open a new conversation in claude.ai
2. Upload: CLAUDE.md, APP_AS_IS.md, BACKLOG.md
3. Say: "Read these documents. This is the QFit Website project. Let's plan what to do next."
4. After planning, go to Claude Code to implement

---

## Ending a Session

In Claude Code:
```
Please update CLAUDE.md, APP_AS_IS.md and BACKLOG.md 
with what we achieved today.
```

Then:
```bash
git add .
git commit -m "session: [short description of what was done]"
git push
```

---

## Handing off to colleague (WordPress)

When a section is ready for WordPress:
1. Make sure CONTENT.md has all the text for that section
2. Make sure the HTML is clean and commented
3. Create a GitHub Issue describing what needs to be done in WordPress
4. Tag the colleague in the issue

---

*Last updated: 2026-04*
