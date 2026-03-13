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
# Common GitHub Commands for Students
# This guide explains each command and shows how to use it
# with the "Complex-Calculator-C" repository.


1. Initialize a new repository
git init
# Explanation: Creates a new Git repository in the current folder.
# Example:
cd Complex-Calculator-C
git init

2. Clone an existing repository
git clone <repository-url>
# Explanation: Copies a repository from GitHub to your computer.
# Example:
git clone https://github.com/username/Complex-Calculator-C.git

3. Check repository status
git status
# Explanation: Shows which files have been modified, staged, or untracked.
# Example:
git status

4. Stage changes
git add <filename>
git add .
# Explanation: Prepares files to be committed. "git add ." stages all files.
# Example:
git add calculator.c
git add README.md

5. Commit changes
git commit -m "Your commit message"
# Explanation: Saves staged changes into the repository history.
# Example:
git commit -m "Added factorial function to calculator"

6. Push changes to GitHub
git push origin main
# Explanation: Uploads local commits to the GitHub repository.
# Example:
git push origin main

7. Pull latest changes from GitHub
git pull origin main
# Explanation: Downloads and merges changes from GitHub into your local repo.
# Example:
git pull origin main

8. Create a new branch
git branch <branch-name>
# Explanation: Creates a new branch for separate development.
# Example:
git branch feature-logarithm

9. Switch to another branch
git checkout <branch-name>
# Explanation: Moves you to the branch you specify.
# Example:
git checkout feature-logarithm

10. Merge a branch into main
git checkout main
git merge <branch-name>
# Explanation: Combines changes from another branch into main.
# Example:
git checkout main
git merge feature-logarithm

11. View commit history
git log
# Explanation: Shows a list of past commits with details.
# Example:
git log

12. Undo changes (reset file to last commit)
git checkout -- <filename>
# Explanation: Restores a file to its last committed state.
# Example:
git checkout -- calculator.c

13. Remove a file from staging
git reset <filename>
# Explanation: Unstages a file that was added with git add.
# Example:
git reset README.md

14. Delete a branch
git branch -d <branch-name>
# Explanation: Deletes a branch locally.
# Example:
git branch -d feature-logarithm
