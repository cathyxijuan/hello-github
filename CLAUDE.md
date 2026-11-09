# CLAUDE.md

## What this repo is for

**Repository:** cathyxijuan/hello-github

This is a personal sandbox for **learning how to use Claude Code**. The owner
uses it to practice asking Claude to do things: editing files, running
commands, using git and GitHub, and trying out Claude Code features.

Nothing here is production code. Experiments are welcome, and files may come
and go as different features get tried out.

---

## How Claude should help here

The goal is learning, not just getting the task done. When working in this
repo:

- **Explain as you go.** Briefly say what you are doing and why, especially
  for git, GitHub, and terminal steps. Assume the owner is still learning
  these tools.
- **Name the feature.** When you use a Claude Code feature (subagents, skills,
  slash commands, hooks, plan mode, CLAUDE.md, etc.), mention it by name so the
  owner learns it exists.
- **Show the commands.** When you run a git or shell command the owner might
  want to run themselves later, show it.
- **Keep changes small.** Make one focused change at a time so each step is
  easy to follow and review.
- **Ask when unclear.** If a request is ambiguous, especially anything that
  deletes or overwrites files, ask before acting.
- **Suggest next steps.** After finishing a task, it's helpful to suggest a
  related thing to try next.

---

## Things not to touch

- **`cathyxijuan/cathyxijuan.github.io` and the ubcsemlab.com website.** That
  repo hosts a lab website. Never push to it, change it, or publish anything
  that would show up under ubcsemlab.com.
- **GitHub Pages for this repo.** Don't enable or deploy GitHub Pages from this
  repo: the account's Pages domain is ubcsemlab.com, so any site published from
  here would appear under the lab's domain.

---

## Repo contents

```
hello-github/
├── .gitignore    # Ignores R/RStudio temp files (.Rproj.user, .Rhistory, .RData)
└── CLAUDE.md     # This file: instructions Claude reads at the start of every session
```

---

## Conventions

- **Encoding:** UTF-8 for all text files
- **Indentation:** 2 spaces, no tabs
- **Default branch:** `master`

### Git workflow

- Work on a `claude/...` branch, never directly on `master`.
- Changes reach `master` through a pull request that the owner reviews and
  merges.
- Commit messages: short, present tense, describe what changed
  (e.g. "Add example R script").
- Push with `git push -u origin <branch-name>`.
- Never force push or rewrite history without explicit permission.
- Don't commit secrets, credentials, or RStudio temp files.
