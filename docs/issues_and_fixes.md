# Issues and Fixes

## Issue 1: Git Push Failed

Problem:
fatal: No configured push destination

Cause:
Remote repository was not linked to local repo

Fix:

* Created GitHub repository
* Added remote:
  git remote add origin <repo_url>
* Pushed using:
  git push -u origin main

Learning:
Always connect local repo to remote before pushing

---

## Issue 2: Forgot WSL sudo password

Fix:

* Opened WSL as root:
  wsl -u root
* Reset password using:
  passwd <username>

Learning:
Keep credentials documented securely

