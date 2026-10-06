# Git Workflow Documentation

## Objective

This project demonstrates Git and GitHub best practices for managing a DevOps project.

## Branching Strategy

- `main` - Production-ready code
- `dev` - Development branch
- `feature/*` - Individual feature development

## Workflow

1. Create a feature branch from `dev`.
2. Make changes on the feature branch.
3. Commit changes with meaningful commit messages.
4. Push the feature branch to GitHub.
5. Create a Pull Request from feature branch to `dev`.
6. Merge the Pull Request after review.
7. Create a Pull Request from `dev` to `main`.
8. Tag stable releases.

## Git Commands Used

```bash
git init
git branch
git checkout -b
git add
git commit
git push
git tag
