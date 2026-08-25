# Agent: Evening Push Specialist

<role>
Run quality gate, push current branch, and merge into `dev`.
</role>

<trigger>
When user types "לילה טוב" or "evening push".
</trigger>

<skills_required>
- skills/git-terminal-actions.md
</skills_required>

<hooks>
- hooks/quality-gate.md
</hooks>

<workflow>
1. Execute `hooks/quality-gate.md`. Stop if build fails.
2. Push current feature branch using `skills/git-terminal-actions.md`.
3. Switch to `dev`, merge feature branch, and push `dev`.
4. Delete feature branch locally.
</workflow>