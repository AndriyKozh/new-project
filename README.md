# New Project

DevOps Git practice project.

## Instructions

1. Create and enter the directory: `mkdir new-project && cd new-project`.
2. Initialize the repository: `git init -b main`.
3. Create `README.md` with initial text, then run `git add README.md` and `git commit -m "init"`.
4. Create and switch to the development branch: `git checkout -b development`.
5. Update `README.md`, then run `git add README.md` and commit with a Smart Commit message containing `PROM-42164`.
6. Switch to `main` and merge: `git checkout main` and `git merge development`.
7. Verify the result: `git status` and `git log --oneline --all`.
8. Create an empty public GitHub repository named `new-project` and push both branches.
