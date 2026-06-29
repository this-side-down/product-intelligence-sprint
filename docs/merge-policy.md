# Merge policy

All changes land through pull requests. There is no direct push-to-`main` workflow for routine updates.

## Auto-merge

When a pull request is opened or updated against `main`, the [auto-merge workflow](../.github/workflows/auto-merge.yml) squash-merges it automatically if:

- the PR is not a draft
- the head branch is in this repository (not a fork)
- GitHub reports the PR as mergeable

Branches are deleted after merge.

## Implications

- Keep PRs small and reviewable in the diff — auto-merge does not wait for human approval
- Use draft PRs when work is not ready to land
- Resolve merge conflicts before expecting auto-merge to succeed
