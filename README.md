# ⚡Git Conflicts Resolution Workshop⚡

* Use the example repository in the `git-workshop` folder to practice resolving conflicts
* There will be breaks for you to work on each Mini-Lab
* Each lab contains hands-on exercises to reinforce learning

## 📋 Pre-Lab Requirements

**1. Git Setup**
* Install Git on your machine if you haven't already
* Configure your Git credentials:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

**2. Repository Setup**
* Fork the repository by clicking the 'Fork' button at the top right of this page
* Clone your forked repository:
```bash
git clone https://github.com/YOUR-USERNAME/git-workshop.git
cd git-workshop
```
* Add the original repository as upstream:
```bash
git remote add upstream https://github.com/ORIGINAL-OWNER/git-workshop.git
```

**3. Verify Setup**
* Check your Git configuration:
```bash
git config --list
```
* Verify remotes are set correctly:
```bash
git remote -v
```

><details>
><summary>🔧 Troubleshooting Setup</summary>
>
>If you encounter issues:
>```bash
># Check Git installation
>git --version
>
># Check repository status
>git status
>
># View all branches
>git branch -a
>```
></details>

## 🛠️ Mini Lab 1: Git Rebase Fundamentals

**Exercise 1.1**: Understanding Basic Rebase
* Description of what you'll learn
* Key concepts covered
* Expected outcome

><details>
><summary>🎥 Basic Rebase Demo Video</summary>
>
>https://your-video-link-here
>
></details>

**Exercise 1.2**: Interactive Rebase
* Description of what you'll learn
* Key concepts covered
* Expected outcome

><details>
><summary>🎥 Interactive Rebase Demo Video</summary>
>
>https://your-video-link-here
>
></details>

**Exercise 1.3**: Resolving Rebase Conflicts
* Description of what you'll learn
* Key concepts covered
* Expected outcome

><details>
><summary>✨ Helpful Rebase Commands</summary>
>
>```bash
># View current branch structure
>git log --graph --oneline --all
>
># Start interactive rebase
>git rebase -i HEAD~3
>```
></details>

## 🧠 Mini Lab 2: Merge Conflict Resolution

**Exercise 2.1**: Basic Merge Conflicts
* Description of what you'll learn
* Key concepts covered
* Expected outcome

><details>
><summary>🎥 Basic Merge Demo Video</summary>
>
>https://your-video-link-here
>
></details>

**Exercise 2.2**: Multiple File Conflicts
* Description of what you'll learn
* Key concepts covered
* Expected outcome

><details>
><summary>✨ Helpful Merge Commands</summary>
>
>```bash
># Check merge status
>git status
>
># View conflict differences
>git diff
>```
></details>

## 🤔 Mini Lab 3: Advanced Git Operations (Bonus)

**Exercise 3.1**: Cherry-Pick Operations
* Description of what you'll learn
* Key concepts covered
* Expected outcome

**Exercise 3.2**: Reset and Recovery
* Description of what you'll learn
* Key concepts covered
* Expected outcome

><details>
><summary>✨ Advanced Git Commands</summary>
>
>```bash
># Cherry pick a commit
>git cherry-pick <commit-hash>
>
># Reset to previous state
>git reset --hard HEAD~1
>```
></details>

## 📚 Resources
* [Git Documentation](https://git-scm.com/doc)
* [Pro Git Book](https://git-scm.com/book/en/v2)
* [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

⚙️ Basic Git knowledge is required for this workshop\
⚠️ Git commands can be destructive, so make sure to back up your work before starting
