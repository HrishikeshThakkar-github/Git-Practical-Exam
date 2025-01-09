# Git-Practical-Exam

## Overview
This exercise involves practicing key Git concepts and commands, including `git-flow`, branching, squash, reset, rebase, cherry-pick, and more. Follow the steps below to complete the tasks and reinforce your Git skills.

---

## Steps to Complete

1. **Repository Setup**
   - Create a new repository using a template.
   - Initialize `git-flow`.

2. **Feature Branch**
   - Create a feature branch for project setup using the proper Zoho task ID format (e.g., `TP2-T1299_Project_Setup`).
   - Create a sub-branch from the project setup branch and practice the following operations:
     - **Squash**
     - **Reset**
     - **Rebase**
     - **Cherry-pick**

3. **Commit Management**
   - Create a branch from `develop`.
   - Add a commit message hook to the repository.
   - Perform multiple commits in the new branch.
   - Create a PR to `develop` with the following considerations:
     - PR should be small and focus on one commit per PR if possible.
     - For one-liner fixes, multiple commits can be grouped into a single PR.

4. **Handling Multiple Branches**
   - Create another branch from `develop` while your previous PR is still under review.
   - Commit changes to your current branch and push them.
   - Once your previous PR is merged into `develop`:
     - Ensure your branch is updated with the latest changes from `develop`.
     - Create a PR for the current branch.

5. **Version Tagging**
   - Add version tags to specific commits for tracking new build releases.

6. **Branch Operations**
   - Create two additional branches (`branch-3` and `branch-4`) from `develop`:
     - Push README changes to `branch-3`.
     - Cherry-pick `branch-3`'s commit into `branch-4`.
     - Update the commit message in `branch-4`.
     - Add three commits to `branch-4` and delete the last commit.

---

## Key Concepts Practiced
- `git-flow` initialization and branching strategy.
- Effective commit and PR management.
- Resolving branch conflicts and updating branches.
- Cherry-pick, squash, reset, and rebase operations.
- Version tagging for releases.

---

This exercise is designed to enhance your Git proficiency and prepare you for real-world version control scenarios.
