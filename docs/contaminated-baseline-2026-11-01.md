# Contaminated baseline run (2026-11-01) - comparison only

Not a valid RED baseline: the subagent inherited a project CLAUDE.md and cited "project rules require a grill".

Key behavior:
- Read the repo first.
- Asked 6 questions, each with a default: audience, call to action, replace vs standalone, prices shown, photos available, deadline.
- Then planned 5 approaches and a branch.
- Would not publish.

Use: compare against the clean run (`docs/red-baseline-prompt.md`). A clean agent that skips questions and builds a generic page is the failure this skill targets.
