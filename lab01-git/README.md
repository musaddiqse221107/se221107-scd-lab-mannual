# Lab 1 — Git Fundamentals

Activities completed: repository setup, Maven skeleton, feature-branch workflow, deliberate merge-conflict exercise, conflict resolution, remote integration and CI preparation.

### Feature branch vs trunk-based
Feature branches isolate a focused change for review. Trunk-based development keeps branches short-lived and integrates frequently. For a four-person capstone I would use short-lived feature branches with frequent merges to main because this preserves reviewability while limiting divergence.

### .gitignore
Maven `target/` and compiled classes are generated; IDE/OS metadata is local; logs are runtime artifacts.

### Required evidence
Use `git log --graph --oneline --decorate --all` for the commit graph. For the manual's conflict screenshot, capture the real conflict markers, resolved file, and final `git status` from the terminal/editor. This repository does not fabricate screenshots.