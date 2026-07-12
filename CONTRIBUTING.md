# Contributing

Thanks for your interest in contributing. This document outlines how work gets picked up, developed, and merged across our repositories.

## Access model

Most collaborators have **read-only** access to repositories. To contribute, you'll need to **fork** the relevant repository and submit changes via pull request from your fork. Only designated reviewers listed below have write/merge access to the main repositories.

## 1. Find or create a task

All work is tracked as **GitHub Issues**, organized on our [project board](https://github.com/orgs/Cerify-Systems/projects/3).

- Check the board first for an existing, unassigned issue matching the work you want to do.
- **If no matching issue exists, create one before starting any work.** Describe the problem or feature clearly so it can be tracked and assigned.
- Get the issue assigned to you before starting, to avoid duplicate effort.

## 2. Fork and branch

- Fork the repository to your own account.
- Create your working branch **from `dev`**, using a descriptive name (e.g. `fix/issue-123-login-bug`).
- Note: the default branch across our repositories is `prod`. Do not branch from or raise pull requests against `prod` — all work branches from and targets `dev`.

## 3. Keep your branch up to date

Before opening a pull request — and again if time has passed before it's merged — update your branch with the latest `dev`:

```bash
git fetch upstream
git pull upstream dev
```

Resolve any conflicts locally and push the updated branch to your fork.

## 4. Open a pull request

- Target the **`dev`** branch of the upstream repository. Do not raise pull requests against `prod`.
- Reference the issue your PR addresses (e.g. `Closes #123`).
- Fill out the PR template checklist completely.
- Assign one of the following as reviewer: [@BitByNIK](https://github.com/BitByNIK), [@Phaneesh-Katti](https://github.com/Phaneesh-Katti), [@nytrixis](https://github.com/nytrixis), [@subodhvsharma](https://github.com/subodhvsharma).

## 5. Review and merge

- **Update the project board:** As soon as you open a pull request, move the corresponding issue to the **"In Review"** column on the project board (do not mark it as closed/done yet).
- Address review feedback with additional commits to the same branch.
- Once approved, a reviewer will merge the pull request, which will automatically close the issue and mark it as done.
- Only the reviewers listed above have merge permissions; contributors should not attempt to merge their own PRs.

## Questions?

If anything here is unclear, open an issue or reach out via [support@cerify.ai](mailto:support@cerify.ai).
