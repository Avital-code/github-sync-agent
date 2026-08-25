# Rule: Git Branch Policy

<rules>
1. `main`: Production-only branch. No direct commits.
2. `dev`: Active integration branch for all team members.
3. `feature/*`: Created from `dev` for specific tasks.
4. Always delete local feature branches after successful merge into `dev`.
</rules>