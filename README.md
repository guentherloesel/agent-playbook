# Agent Playbook

Reusable instructions, templates, and snippets for Codex and other coding agents.

This repository is intended as a source of truth for personal agent workflows. Copy
the relevant files into project repositories when they should apply to that
project directly.

## Structure

- `agents/`: Reusable `AGENTS.md` templates for repository-level instructions.
- `skills/`: Reusable `SKILL.md` templates and task-specific skill drafts.
- `snippets/`: Small instruction blocks that can be copied into app settings,
  `AGENTS.md`, or skills.

## Snippets

- `snippets/git-commit-policy.md`: Git staging and commit approval rules.
- `snippets/task-handoff-checklist.md`: Final review checklist before handing
  work back to a user.

## Usage

Use this repository to maintain shared guidance, then place concrete instructions
inside each target repository. Repo-local files should always reflect the rules
that truly apply to that codebase.
