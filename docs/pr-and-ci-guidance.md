# PR & CI Guidance

Purpose: reduce review churn, speed merges, and increase reliability.

PR size and scope
- Prefer PRs <= 400 lines of code and focused on a single logical change.
- For large changes, split into an integration PR that wires up the pieces + follow-ups that fill in details.

PR description requirements
- Link to the related issue(s)
- Short summary of the change
- Acceptance criteria (how the reviewer verifies the change)
- Testing notes (how to run locally + CI expectations)
- Any roll-forward or migration steps (if applicable)

CI gating
- All PRs must pass automated tests (unit + linters) and security scans before merge.
- Required status checks: unit tests, lint, security-scan, integration (if applicable).
- Document intermittent CI flakiness in the PR and add a follow-up task for stabilizing tests.

Review and merging
- At least one approval required; for high-risk or cross-team work, require two reviewers including the Technical Lead or designee.
- Use squash merge for single-feature PRs; include issue number in commit message.
- If blocking issues are found during review that are out of scope for the PR, create follow-up issues and request re-review after fixes.

PR checklist (to include in PR template)
- [ ] PR description complete with issue link and acceptance criteria
- [ ] Tests added/updated and passing in CI
- [ ] Documentation updated (if applicable)
- [ ] Reviewer(s) assigned
