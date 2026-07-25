# dotfiles

> Early-stage dotfiles for a streamlined Linux terminal and shell setup.

## Status

This repository is a **personal work-in-progress**.  
Right now it primarily contains:

- Terminal configuration (prompt, colors, fonts)
- Shell settings and aliases (e.g. Bash/Zsh/Fish)
- A few Git and CLI quality-of-life tweaks

More tooling (editor, window manager, etc.) may be added over time as I consolidate my setup.

## Purpose

The goal of this repo is to:

- Keep my terminal and shell configuration under version control.
- Make it easy for me to bootstrap a familiar environment on new machines.
- Document how my daily-driver Linux terminal is configured.

You’re welcome to browse and copy ideas, but these configs are tuned to my workflow.

Directory layout will evolve, but a simple structure might be:

```text
dotfiles/
  shell/       # Shell configs (rc files, aliases, functions)
  terminal/    # Terminal emulator configs
  git/         # Git config and ignores
  install.sh   # Optional bootstrap / symlink script
```

## Contributions

At this time, I’m **not accepting contributions or pull requests**.

These dotfiles are intentionally:

- Opinionated and tailored to my personal environment.
- Subject to change without notice as I iterate on my setup.

If you find something useful, feel free to copy or adapt it in your own dotfiles repo.
