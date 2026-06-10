# Skill Name

Use this skill when the user asks for work that matches this workflow.

## When To Use

- Use this skill for clearly scoped tasks in this domain.
- Do not use this skill for unrelated general coding tasks.

## Workflow

1. Identify the relevant files, tools, and checks.
2. Read existing project instructions before making changes.
3. Make the smallest change that solves the task.
4. Run the relevant validation steps.
5. Summarize the result, changed files, and any remaining risk.

## Rules

- Prefer project-local conventions over generic defaults.
- Do not edit generated files unless the task explicitly requires it.
- Do not commit without explicit user approval.

## Validation

- Run the narrowest useful check first.
- Broaden validation when the change touches shared behavior or public interfaces.
