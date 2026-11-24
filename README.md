# merge-queue-sandbox

Disposable sandbox to test the GitHub merge queue. Dummy workflows only.

- `fail-fast.flag` in a PR: the `pull_request` fast lane fails.
- `fail-full.flag` in a PR: the `merge_group` full suite fails, the PR is ejected from the queue.
