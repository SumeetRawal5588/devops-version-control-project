# DevOps Version Control Project

This project demonstrates Git and GitHub version-control best practices as part of the DevOps internship.

## Objectives

* Manage a DevOps project using Git
* Follow a proper branching strategy
* Use Pull Requests for merging
* Maintain project documentation
* Use `.gitignore`
* Create and manage Git tags

## Branching Strategy

```text
main
  ↑
 dev
  ↑
feature/project-documentation
```

### Branches

* `main` — Production-ready code
* `dev` — Development branch
* `feature/*` — Feature development

## Git Workflow

1. Create a feature branch from `dev`.
2. Make and test changes.
3. Commit changes with meaningful messages.
4. Push the feature branch to GitHub.
5. Create a Pull Request from feature branch to `dev`.
6. Merge after review.
7. Create a Pull Request from `dev` to `main`.
8. Tag stable versions.

## Project Structure

```text
Task_4/
├── README.md
├── .gitignore
└── docs/
    └── git-workflow.md
```

## Git Commands Practiced

```bash
git init
git branch
git checkout -b
git add
git commit
git push
git pull
git log
git tag
git show
```

## Pull Requests

* Feature → `dev`
* `dev` → `main`

## Version

`v1.0.0`

## Outcome

Learned and implemented a basic Git-based DevOps version-control workflow using branches, commits, Pull Requests, documentation, `.gitignore`, and Git tags.
