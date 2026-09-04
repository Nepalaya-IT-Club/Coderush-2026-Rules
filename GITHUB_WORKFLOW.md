# GitHub Workflow — How Projects Should Be Pushed

This document explains how every team must set up, branch, commit, and submit their project on GitHub during **CodeRush 2026**.

---

## 2.1 Repository Setup

1. Each team must create a **single GitHub repository** for their project, under this GitHub organization, before the event begins or at the start of the hackathon.
2. The repository must be set to **Public** so that judges and organizers can access and review the code.
3. The repository name should follow this format:
   ```
   team-name-coderush2026
   ```
4. Add all team members as **collaborators** on the repository.
5. Add the **Nepalaya IT Club GitHub organization** (or the official CodeRush 2026 GitHub account) as a **collaborator** on the repository, so organizers and judges can review commits, branches, and pull requests throughout the event.
   - Go to your repository → **Settings** → **Collaborators and teams** → **Add people**
  - Search for and add: `@Nepalaya-IT-Club`
   - Grant at least **Read** access; **Write** access is fine if you'd like organizers to help troubleshoot.

## 2.2 Branching Rules

- The `main` branch should always contain a stable, working version of the project.
- Each team member should work on a separate feature branch, named clearly, for example:
  ```
  feature/login-page
  feature/api-integration
  fix/navbar-bug
  ```
- **Do not push directly to `main`.** All changes should be merged through a Pull Request (PR), even within the same team, to keep a clean project history.

## 2.3 Commit Guidelines

- Commit frequently with clear, descriptive commit messages. Avoid vague messages like `"update"` or `"fix"`.
- Good commit message format:
  ```
  Add: user authentication with JWT
  Fix: navbar not responsive on mobile
  Update: README with setup instructions
  ```
- Each commit should represent **one logical change**, not a mix of unrelated edits.

## 2.4 Pull Requests & Code Review

- Open a Pull Request when a feature or fix is ready to be merged into `main`.
- At least one other team member should review the PR before merging, where possible, to catch bugs early.
- Resolve merge conflicts carefully — do **not** force-push over a teammate's work.

## 2.5 Final Submission

- The final, working version of the project must be merged into the `main` branch before the submission deadline.
- Teams must submit their GitHub repository link through the official submission form provided by the organizers.
- Ensure the repository is **not modified after the submission deadline**. Any commits after the deadline will not be considered during judging.

---

⬅️ [Back: Code of Conduct](./CODE_OF_CONDUCT.md) | ➡️ [Next: README Template](./README_TEMPLATE.md)
