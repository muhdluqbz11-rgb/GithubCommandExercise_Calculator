# Complex Calculator in C

A menu-driven calculator program written in **C** that supports both basic and advanced mathematical operations.  
This project is designed as a learning example for students to practice programming and GitHub workflows.

---

## ✨ Features
- Addition, subtraction, multiplication, division
- Power function (exponentiation)
- Square root calculation
- Factorial of integers
- Error handling (division by zero, negative inputs for square root/factorial)

---
📘 Common GitHub Commands for Students
This section explains the most useful GitHub commands for beginners, with examples using the Complex-Calculator-C project.

1. Initialize a New Repository
bash
git init
Explanation: Creates a new Git repository in the current folder.
Example:

bash
cd Complex-Calculator-C
git init
2. Clone an Existing Repository
bash
git clone <repository-url>
Explanation: Copies a repository from GitHub to your computer.
Example:

bash
git clone https://github.com/username/Complex-Calculator-C.git
3. Check Repository Status
bash
git status
Explanation: Shows which files have been modified, staged, or untracked.
Example:

bash
git status
4. Stage Changes
bash
git add <filename>
git add .
Explanation: Prepares files to be committed. git add . stages all files.
Example:

bash
git add calculator.c
git add README.md
5. Commit Changes
bash
git commit -m "Your commit message"
Explanation: Saves staged changes into the repository history.
Example:

bash
git commit -m "Added factorial function to calculator"
6. Push Changes to GitHub
bash
git push origin main
Explanation: Uploads local commits to the GitHub repository.
Example:

bash
git push origin main
7. Pull Latest Changes from GitHub
bash
git pull origin main
Explanation: Downloads and merges changes from GitHub into your local repo.
Example:

bash
git pull origin main
8. Create a New Branch
bash
git branch <branch-name>
Explanation: Creates a new branch for separate development.
Example:

bash
git branch feature-logarithm
9. Switch to Another Branch
bash
git checkout <branch-name>
Explanation: Moves you to the branch you specify.
Example:

bash
git checkout feature-logarithm
10. Merge a Branch into Main
bash
git checkout main
git merge <branch-name>
Explanation: Combines changes from another branch into main.
Example:

bash
git checkout main
git merge feature-logarithm
11. View Commit History
bash
git log
Explanation: Shows a list of past commits with details.
Example:

bash
git log
12. Undo Changes (Reset File to Last Commit)
bash
git checkout -- <filename>
Explanation: Restores a file to its last committed state.
Example:

bash
git checkout -- calculator.c
13. Remove a File from Staging
bash
git reset <filename>
Explanation: Unstages a file that was added with git add.
Example:

bash
git reset README.md
14. Delete a Branch
bash
git branch -d <branch-name>
Explanation: Deletes a branch locally.
Example:

bash
git branch -d feature-logarithm
