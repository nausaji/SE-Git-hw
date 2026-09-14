# SE-Git-hw

A practice repository for CINS 5318 Assignment #1, demonstrating core Git and GitHub workflows: repository setup, branching, pull requests, merge conflict resolution, and issue tracking.

## Files

- `hello.py` — a simple "Hello, World!" program, later updated to accept user input.
- `apple.py` — a small feature added on the `feature-1` branch, printing "I eat apple".

## Git Workflow Summary

1. **Initial Commit** — Created the repository, cloned it locally, and committed `hello.py`.
2. **Branching** — Created a `feature-1` branch and added `apple.py`.
3. **Pull Request** — Opened a pull request to merge `feature-1` into `main`, then merged it.
4. **Merge Conflict** — Simulated a conflict by editing the same line of `hello.py` on two separate branches (`branch-a` and `branch-b`), then resolved it manually by editing the file and committing the resolution.
5. **Issues** — Created and tracked issues in the GitHub Issues tab, closing them via commit messages (e.g. `closes #1`).

## Issues Tracked

- **#1** — Add input validation to `hello.py` (assigned to self, closed)
- **#2** — Add comments explaining `apple.py` (assigned to a classmate)

## Author

nausaji
