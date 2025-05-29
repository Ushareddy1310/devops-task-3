# 🚀 DevOps Task 4: Version-Controlled Project with Git

Welcome to my DevOps Task 4 project! This repository demonstrates **best practices in version control** using Git and GitHub.  
I managed branches, pull requests, tags, and documentation to simulate a real-world DevOps workflow.

---

## 🎯 Project Objective

Master Git workflows and version control by:

- Using multiple branches (`main`, `dev`, `feature`)  
- Creating and merging pull requests for code reviews  
- Managing `.gitignore` to keep repo clean  
- Tagging releases for version tracking  
- Documenting all work with clear markdown files  

---

## 🗂️ Project Highlights

| Feature            | Description                                     |
|--------------------|------------------------------------------------|
| Branching Strategy | Separate branches for development and features |
| Pull Requests      | Used for merging and code reviews               |
| Tags               | Marked release points with semantic versioning |
| Documentation      | README and TASK4.md files for clear explanation |
| .gitignore         | Excludes unnecessary files like logs, env files |

---

## 📚 How to Use This Repo

1. **Clone the repo:**

   ```bash
   git clone https://github.com/Ushareddy1310/devops-task-3.git
   cd devops-task-3
2. **Checkout the development branch:**

   ```bash
   git checkout dev
3. **Create a new feature branch:**

   ```bash
   git checkout -b feature/your-feature-name
4. **Make your changes, commit, and push:**

   ```bash
   git add .
   git commit -m "feat: add description of your change"
   git push origin feature/your-feature-name
5. **Create a Pull Request (PR):**

   - Go to your GitHub repo in a browser.
   - You’ll see a prompt to compare & create a pull request for your pushed branch—click it.
   - Make sure the base branch is `dev` (or whatever branch you want to merge into).
   - Add a clear title and description explaining your changes.
   - Click **Create pull request**.
6. **Merge the Pull Request:**

   - Review the changes in the PR.
   - If everything looks good, click **Merge pull request**.
   - Confirm the merge by clicking **Confirm merge**.
   - Optionally, delete the feature branch by clicking **Delete branch**.
7. **Sync your local `dev` branch:**

   ```bash
   git checkout dev
   git pull origin dev
8. **Merge `dev` into `main` and tag the release:**

   ```bash
   git checkout main
   git merge dev
   git tag -a v1.0.0 -m "Release version 1.0.0"
   git push origin main --tags
9. **Summary:**

This project demonstrates:

- Using branches to isolate features and development  
- Creating pull requests for code review and collaboration  
- Merging changes cleanly into the main codebase  
- Using tags to mark release versions  
- Keeping the repo clean with `.gitignore`  
- Documenting your process with markdown files  

Feel free to explore the repo and try these workflows yourself!


