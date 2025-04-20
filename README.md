# 🎯 git — Version Control System

**git** is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It's widely used for tracking changes in source code during software development.

---

## ✅ Features

- Track changes in files and directories
- Collaborate with others using repositories
- Branching and merging support
- Full history of changes
- Works offline with local repositories

---

## 📦 Installation

### Debian/Ubuntu
```bash
sudo apt install git
```

### Arch Linux
```bash
sudo pacman -S git
```

### macOS (Homebrew)
```bash
brew install git
```

---

## 🚀 Basic Usage

### Initialize a new Git repository
```bash
git init
```

### Clone an existing repository
```bash
git clone https://github.com/user/repository.git
```

### Check the status of files in your repo
```bash
git status
```

### Add files to staging area
```bash
git add filename
```

### Commit changes
```bash
git commit -m "Your commit message"
```

### Push changes to remote repository
```bash
git push origin main
```

---

## ⚙️ Common Commands & Examples

| Option/Flag           | Description                                            |
|-----------------------|--------------------------------------------------------|
| `git log`             | View commit history                                    |
| `git diff`            | View differences between commits or working directory  |
| `git branch`          | List, create, or delete branches                       |
| `git merge <branch>`  | Merge changes from another branch                      |
| `git fetch`           | Fetch changes from remote without merging              |
| `git pull`            | Fetch and merge changes from remote                    |

### Create a new branch and switch to it
```bash
git checkout -b new-feature
```

### Merge another branch into your current branch
```bash
git merge feature-branch
```

---

## 🧩 Tips

- Use `git config --global user.name "Your Name"` and `git config --global user.email "youremail@example.com"` to set up your identity.
- Use `.gitignore` to exclude files from being tracked by git (e.g., compiled files, secrets).
- Git can be used for more than just code—track configurations, docs, and more!

---

## 📚 More Info

- Git Documentation: [https://git-scm.com/doc](https://git-scm.com/doc)  
- GitHub: [https://github.com/git/git](https://github.com/git/git)  
- Run `git --help` or `man git` for additional commands and options
