# bongo-devops-core

Welcome to the **bongo-devops-core** repository. This project is part of the **Git & GitHub Mastery: 10 Mission-Critical Tasks** assignment under the DevOps & Cloud Engineering track by bongoDev.

## 🚀 Mission Overview
The goal of this track is to transition from a basic "coder" into a strategic **Version Control Strategist** by solving real-world DevOps scenario tasks.

## 🛠️ Phase 1: The Foundations

### Task 01: The "First Impression" (Identity & Setup)
* **Objective:** Establish proper Git attribution and initialize the core project ecosystem.
* **Status:** 🔄 Completed

#### Steps Executed:
1. **Repository Initialization:** Created and initialized this local Git repository.
2. **Global Identity Configuration:** Configured global `user.name` and `user.email` to ensure clean, traceable commit authorship across team operations.
3. **Baseline Documentation:** Authored this initial `README.md` file.
4. **Initial Commit:** Staged and logged the baseline file using Conventional Commits formatting: `chore: initial repository setup`.

---

### Task 02: The "Safe Space" (.gitignore)
* **Objective:** Prevent sensitive infrastructure secrets from leaking into version control.
* **Status:** 🔄 Completed
* **Steps Executed:** Created a `.env` file containing mockup secrets and successfully isolated it from version control tracking by configuring a `.gitignore` baseline rule.

### Task 03: The "Parallel Universe" (Branching)
* **Objective:** Maintain production stability by isolating experimental updates.
* **Status:** 🔄 Completed
* **Steps Executed:** Isolated new work by branching into `feature/system-optimization`, committed `kernel_tuning.txt`, and verified state isolation upon returning to the `main` branch.


### Task 04: The "Selective Memory" (Staging)
* **Objective:** Practice atomic commits by staging and logging unrelated modifications independently.
* **Status:** 🔄 Completed
* **Steps Executed:** Generated `web_fix.conf` and `db_fix.conf`. Utilized intentional staging environments to isolate and commit the web patch ahead of tracking the database patch.

### Task 05: The "Cloud Connection" (GitHub)
* **Objective:** Bridge the localized Git engine with remote team-facing infrastructure.
* **Status:** 🔄 Completed
* **Steps Executed:** Established a tracking link to a remote GitHub repository container and cleanly pushed upstream logs from the `main` architecture.


### Task 06: 

commit ed951f0b97198163472c966daa8b98f65b0d99cd (HEAD -> main, origin/main)
Author: mkmahmud <mahmudulhasanmk434@gmail.com>
Date:   Mon Sep 7 19:50:26 2026 +0600

    fix: apply database connectivity patch

diff --git a/db_fix.conf b/db_fix.conf
new file mode 100644
index 0000000..e69de29


### Task 07: The "Safety Net" (Context Switching)
* **Objective:** Handle emergency context switches safely without losing uncommitted progress.
* **Status:** 🔄 Completed
* **Steps Executed:** Simulated ongoing workspace edits on `feature.py`, stashed changes securely using `git stash` to deploy an urgent hotfix patch on `main.py`, and cleanly restored the development state using `git stash pop`.


### Task 08: The "Clean Merge" (Squash Workflow)
* **Objective:** Maintain a clean, readable production commit history using squash merging.
* **Status:** 🔄 Completed
* **Steps Executed:** Checked out `feature/system-optimization` and simulated rapid iterative trial-and-error commits. Returned to `main` and condensed the fragmented commit chain into a singular, production-ready operational log via `git merge --squash`.


### Task 09: The "Conflict Resolution" (Communication)
* **Objective:** Trigger, isolate, and manually correct divergent code branches.
* **Status:** 🔄 Completed
* **Steps Executed:** Established overlapping updates on the identical index line of `optimization.txt` across `main` and `feature/conflict-branch`. Safely intercepted the resulting merge collision, manually excised conflict markers, unified the architectural intent, and logged the successful resolution commit.


### Task 10: The "Time Machine" (Reflog Recovery)
* **Objective:** Recover detached or orphaned data states following destructive reset operations.
* **Status:** 🔄 Completed
* **Steps Executed:** Committed `deployment.sh` and executed an intentional destructive `git reset --hard HEAD~1` command to wipe working directories. Utilized `git reflog` to track down the detached commit index pointer and successfully restored the file landscape back to active state.
