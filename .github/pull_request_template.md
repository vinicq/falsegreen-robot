<!--
Thanks for sending a pull request. A few notes before you submit:

- Keep this PR small and focused. One logical change per PR.
- Three commits is the comfortable ceiling for review. Squash on merge is the
  default, so you do not need to keep many commits.
- Tests are expected for every behaviour change. See CONTRIBUTING.md.

PR title must follow Conventional Commits:  <type>(<scope>): <description>
Valid types: feat / fix / docs / refactor / test / chore / ci. Examples:

  feat(scanner): flag Should Be True on a string literal (R6)
  fix(scanner): stop flagging a custom verification keyword as C2b
-->

## Summary

<!-- One or two sentences describing the change. -->

## Changes

- ...

## Test plan

- [ ] `pytest -q`
- [ ] `python -m falsegreen_robot src tests` (the tool must stay clean on itself)
- [ ] `ruff check src tests`

## Checklist

- [ ] A new/changed detection rule touches all three places: scanner logic,
      `docs/guide.md` (if a new case), and `tests/`.
- [ ] For a new rule: a test proves it fires on the bad pattern AND a test proves
      it does NOT fire on the legitimate look-alike.
- [ ] HIGH-confidence codes were stress-tested against legitimate look-alikes
      before being set to HIGH (they block commits).
- [ ] No `Co-Authored-By:` AI agent trailers in the commit history.
- [ ] Commit count is reasonable for review (rule of thumb: at most 3).

## Related issues

<!-- Fixes #123, Refs #456 -->
