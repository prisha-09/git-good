# Dummy Merge Conflict Repo

Purpose: Demonstrate a merge conflict by editing the same lines in two branches.

Instructions (from feature-a):
1. **Start on main:** Ensure you're on `main` and up to date.
2. **Merge feature-a first:** `git checkout main && git merge feature-a`
3. **Then merge feature-b:** `git merge feature-b`
4. You should see a merge conflict in README.md because both branches modify the same lines differently.

Conflicting section (feature-a version):
- Line A: This is the FEATURE-A version of the conflict line.
- Line B: Edited by FEATURE-A to force a conflict.
