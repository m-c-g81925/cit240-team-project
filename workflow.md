# Git & GitHub Collaboration Workflow

This document outlines our team's standard routine for contributing code, reviewing changes, and keeping our repository synchronized.

---

## 1. Branching (Create an Isolated Workspace)
Always create a dedicated feature branch off `main` before starting any new task. Do not commit directly to the `main` branch. This keeps unfinished code from breaking the working project.

- **Naming Conventions:** `feature/task-description`, `fix/bug-description`, or `docs/update-description`
- **Commands:**
  ```bash
  git checkout main
  git pull origin main
  git checkout -b feature/your-task-name

  git add .
git commit -m "Add workflow documentation file"

git push -u origin feature/your-task-name

git checkout main
git pull origin main
git branch -d feature/your-task-name  # Deletes local branch after merging