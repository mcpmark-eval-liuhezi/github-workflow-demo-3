# Workflow Audit

This page walks the full end-to-end GitHub workflow — branches, pull requests, issues, and close-out — so the demo shows everything as one tidy story rather than as isolated steps.

## How it all fits together

- **Branch** — Every line of work starts on a dedicated working branch (e.g. `feature/audit-notes`) off the repository's default branch. This keeps changes isolated, reproducible, and reviewable one at a time.
- **Pull request** — A PR opens from the feature branch into the default branch. It contains the actual diff, a description of what changed and why, and a clear title thatworked like a pull request does when it is opened.
- **Issue** — A follow-up issue is attached under the PR's checklist topic. Issues act as the task and ticket layer: they record what needs to be done, split follow-ups into smaller pieces, and create a persistent trail in the discussion that anyone can pick up later.
- **Close-out** — When the checklist is done, the checklist issue is closed as completed while any remaining follow-up stays open with its own open status. The PR remains open until the merged state is intentional, so the demo artifact stays unmerged to demonstrate the loop end to end.

## Owner

| Field | Value |
| --- | --- |
| **Login** | HeziLiu |
| **Display name** | Hezi Liu |
| **Profile** | https://github.com/HeziLiu |
| **Bio** | treat me like a tree |
| **Location** | Beijing/Guiyang |
| **Company** | BUPT/GZU |

---

*This document was created as part of the show-and-tell demo: branch → pull request → issue → close-out, all reviewed end to end on *github-workflow-demo-3*.*
