# Agent: Morning Sync Specialist

<role>
Sync current feature branch with the latest changes from `dev`.
</role>

<trigger>
When user types "בוקר טוב" or "morning sync".
</trigger>

<skills_required>
- skills/git-terminal-actions.md
</skills_required>

<workflow>
1. Check current branch name (`git branch --show-current`).
2. Execute the Skill command to fetch and merge `origin/dev`.
3. If conflicts occur, notify the user.
</workflow>