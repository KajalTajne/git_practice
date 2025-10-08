# Git Assignment – Comprehensive Repository Operations

This repository demonstrates advanced Git workflows, including **branching**, **merging**, **conflict resolution**, **reset operations**, **stashing**, **forking**, and **pull requests**.
It follows a sequence of 7 practical exercises to simulate real-world version control collaboration.

---

## 📘 Assignment Overview

| Task No. | Task Title                       | Description                                                                                                                                        |
| -------- | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1        | **Repository Setup**             | Created and linked a local repository with GitHub. Added `initial.txt` and made the initial commit.                                                |
| 2        | **Remote Repository Operations** | Pushed the initial commit, made remote edits, pulled updates, and demonstrated staging/unstaging of multiple files.                                |
| 3        | **Branching & Pull Request**     | Created branch `g1`, added `g1_file.txt`, pushed to remote, raised and merged a PR into `main`.                                                    |
| 4        | **Local Git Operations**         | Practiced resets (`--soft`, `--mixed`, `--hard`), used `git add -p`, explored diffs between branches, and created local branches `b1`, `b2`, `b3`. |
| 5        | **Branch Merging & Cleanup**     | Performed sequential merges (`b3 → b2 → b1 → main`), resolved merge conflicts in `initial.txt`, and deleted local/remote branches.                 |
| 6        | **Fork Operations**              | Forked the repo, cloned locally, added `forked.txt`, and raised a PR from the forked repo to the original `main`.                                  |
| 7        | **Final Documentation**          | Added a detailed `README.md` summarizing all tasks, Git commands used, and PR links for submission.                                                |

---

## 🧩 Key Git Concepts Demonstrated

* Branching & Pull Requests (`git branch`, `git checkout`, `git merge`)
* Reset Operations (`git reset --soft`, `--mixed`, `--hard`)
* Selective Staging (`git add -p`)
* Conflict Resolution (manual merge + stash conflicts)
* Forking and Remote Collaboration
* File Management (`git rm`, `git revert`)
* Stashing (`git stash`, `git stash pop`)
* Repository Cleanup and Documentation

---

## 🔗 Pull Request Links

| PR No. | Description                             | Link                                                         |
| ------ | --------------------------------------- | ------------------------------------------------------------ |
| 1      | Merge branch `g1` → `main`              | https://github.com/KajalTajne/git_practice/pull/1 
| 2      | Forked repository PR to original `main` | https://github.com/PoojaShashikantPawar/Oasisinfobyte/pulls



---

## 🧾 Recommended Verification Commands

To verify repository states at different stages:

```bash
git status
git log --oneline --graph
git diff
git diff --staged
git branch -a
git remote -v
```
Include screenshots of:

* Pull Request merge confirmations
* `git status` and `git log` outputs
* Conflict resolution in `initial.txt`

---


