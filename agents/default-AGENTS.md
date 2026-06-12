# AGENTS.md instructions

## Working Style

- Prefer small, focused changes that match the existing codebase.
- Read the relevant code before editing.
- Keep unrelated refactors out of task-focused changes.
- Run the most relevant checks before handing work back.
- Report any checks that could not be run.

## Feature Branch Workflow

- When starting new feature work, update the `main` branch first.
- Create a new branch from the updated `main` branch.
- Make feature changes on that branch, not directly on `main`.

## Git Commit Policy

- Automatically stage completed changes when they are ready for review.
- Never wait for a separate instruction to run `git add`.
- Never commit changes without explicit user approval.
- Always propose a short Conventional Commit message after staging.
- Do not include the repository name in the commit message or scope unless explicitly requested.
- Wait for user review and approval before running `git commit`.
- After approval, create the commit on the current branch with the approved message.
- Do not amend, squash, or rewrite commits unless explicitly requested.
