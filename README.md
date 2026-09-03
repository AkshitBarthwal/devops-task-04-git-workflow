# DevOps Git Workflow Project

## Overview

This project demonstrates a structured Git workflow for managing a DevOps project using Git and GitHub.

The repository follows a feature-based development workflow with separate `main` and `dev` branches, Pull Requests, meaningful commits, `.gitignore`, and Git tags.

## Tools Used

- Git
- GitHub
- Markdown

## Repository Structure

```text
devops-task-04-git-workflow/
├── app/
│   └── README.md
├── docs/
│   └── git-workflow.md
├── .gitignore
└── README.md
```

## Branch Strategy

| Branch | Purpose |
|---|---|
| `main` | Stable production-ready code |
| `dev` | Development and integration branch |
| `feature/*` | Individual feature development |

## Git Workflow

1. Initialize the Git repository.
2. Create and maintain the `main` branch.
3. Create a `dev` branch for development.
4. Create a feature branch from `dev`.
5. Make changes and commit them with meaningful commit messages.
6. Push the feature branch to GitHub.
7. Create a Pull Request targeting `dev`.
8. Review and merge the Pull Request into `dev`.
9. Delete the completed feature branch.
10. Merge `dev` into `main`.
11. Create a Git tag for the stable release.

## Pull Request Workflow

The project uses Pull Requests to integrate feature work into the development branch.

```text
feature/add-project-documentation
                ↓
          Pull Request
                ↓
               dev
                ↓
          Release Merge
                ↓
              main
```

## Versioning

The stable project release is tagged as:

```text
v1.0.0
```

## Git Best Practices Demonstrated

- Meaningful commit messages
- Feature-based branching
- Separate development and production branches
- Pull Request based integration
- `.gitignore` usage
- Remote branch management
- Release tagging
- Clean working tree

## Outcome

This project demonstrates practical Git and GitHub version-control workflows commonly used in DevOps environments.

## Author

**Akshit Barthwal**

BCA Student | Aspiring DevOps Engineer
