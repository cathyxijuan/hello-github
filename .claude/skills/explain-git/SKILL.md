---
name: explain-git
description: Explain a git command in beginner-friendly terms, breaking down each part and flagging risks. Use when the user runs /explain-git.
argument-hint: "[git command]"
---

Explain this git command for a beginner: $ARGUMENTS

If no command was given above, explain the most recent git command run in this
session. If no git command has been run yet, say so and ask which one to explain.

Format the answer as a few short bullet points:

- **What it does:** one or two plain-language sentences. Avoid jargon, or
  define it when you must use it.
- **Breakdown:** each part of the command (the subcommand, every flag, branch
  names, remotes, file paths) and what it means.
- **Risk:** if the command can lose work or rewrite history (for example
  `reset --hard`, `push --force`, `rebase`, `clean -f`, `checkout -- <file>`,
  `branch -D`), warn clearly and suggest a safer alternative. If it is safe,
  say so in one line.

Keep it short. No long essays. Do not run the command; only explain it.
