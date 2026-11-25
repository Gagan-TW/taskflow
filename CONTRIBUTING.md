# Contributing to TaskFlow

Thank you for contributing! This guide explains how we work together on TaskFlow.

## Golden rules

- Never commit directly to `main`.
- Every change goes through a pull request (PR).
- Every PR is reviewed by the other contributor before it is merged.
- Talk to each other before changing shared parts, such as the database structure or API endpoints.
- If you change how something works, update the related documentation in the same PR.

## Workflow

1. **Get the latest code**

   ```bash
   git checkout main
   git pull
   ```

2. **Create a branch for your task**

   ```bash
   git checkout -b feature/task-assignment
   ```

3. **Make your changes and commit them**

   ```bash
   git add .
   git commit -m "feat: add task assignment endpoint"
   ```

4. **Push your branch to GitHub**

   ```bash
   git push -u origin feature/task-assignment
   ```

5. **Open a pull request** on GitHub into `main`, and fill in the PR template.
6. **Respond to the review.** Make any requested changes and push them to the same branch.
7. **Merge** once the PR is approved, then delete the branch.

## Branch names

Use the format `type/short-description`, in lowercase, with hyphens between words.

| Type | Use it for | Example |
|---|---|---|
| `feature/` | A new feature | `feature/user-login` |
| `fix/` | A bug fix | `fix/task-status-update` |
| `docs/` | Documentation only | `docs/api-reference` |
| `chore/` | Setup and maintenance | `chore/add-eslint` |
| `test/` | Adding or fixing tests | `test/auth-endpoints` |

## Commit messages

Use the format `type: short description`, written as a command (for example, "add", not "added").

| Type | Meaning | Example |
|---|---|---|
| `feat` | A new feature | `feat: add project search` |
| `fix` | A bug fix | `fix: reject expired tokens` |
| `docs` | Documentation | `docs: update README setup steps` |
| `test` | Tests | `test: add login endpoint tests` |
| `refactor` | Code change that doesn't change behaviour | `refactor: move validation into service` |
| `chore` | Setup or maintenance | `chore: add .gitignore entries` |

## Pull requests

- Keep each PR small and focused on one task.
- Link the related issue, for example: `Closes #12`.
- Explain what you changed and how you tested it.

## Reviewing a pull request

- Check that the change works and follows this guide.
- Check that the documentation is updated.
- Give clear, kind and specific feedback.

## Questions

If anything is unclear, ask before you start. It saves time for both of us.