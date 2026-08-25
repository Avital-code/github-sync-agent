# Hook: Quality Gate Check

<trigger_type>
On Completion (Before Push/Merge)
</trigger_type>

<actions>
1. Check that code compiles or runs without errors.
2. If syntax errors exist: stop execution, do not push, and notify user.
</actions>