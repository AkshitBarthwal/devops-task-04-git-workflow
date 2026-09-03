# Git Workflow

This project follows a structured Git workflow for managing DevOps changes.

## Branch Strategy

- `main` — stable production-ready code
- `dev` — development and integration branch
- `feature/*` — individual feature development

## Development Workflow

1. Create a feature branch from `dev`.
2. Make and test the required changes.
3. Commit changes with a meaningful commit message.
4. Push the feature branch to GitHub.
5. Open a Pull Request targeting `dev`.
6. Review and merge the Pull Request.
7. After testing, merge `dev` into `main`.
8. Create a Git tag for a stable release.
