# Git Quickstart Cheat Sheet

## What is Git?
Git is a version control system. It helps you track changes in your code and collaborate with others when combined with GitHub (or simliar). You can always go back to previous versions and work together safely.

## 1. Install Git
- **Windows:** Download and install from [git-scm.com](https://git-scm.com/)
- **macOS:** Use Homebrew: `brew install git`
- **Linux:** Use your package manager, e.g. `sudo apt install git`

## 2. Open a Terminal
- **Windows:** Use "Git Bash" (installed with Git) or the Windows Terminal.
- **macOS/Linux:** Use the standard Terminal app.

All following commands are entered in your terminal/command line.

## 3. Clone a Repository
This copies a project from GitHub (or another server) to your computer.

```bash
git clone <repository-url>
```
Example for this course:
```bash
git clone https://github.com/faensi/python_seminar
```

## 4. Change into the Project Directory
```bash
cd repository
```

## 5. (Optional) Check the Status
See which files have changed:
```bash
git status
```

---

**Why use GitHub (or similar services)?**
- share code with others
- work with others on the same project
- undo mistakes
- code is safely backed up online

---

## Git vs. GitHub (and similar)
- **Git** is a program on your computer for version control. You can use it locally, without the internet.
- **GitHub** (or similar providers like GitLab, Bitbucket) is an online service that hosts your code repositories and makes collaboration easy. It is not Git itself, but a platform that uses Git.
- You use Git to manage your code, and GitHub to share it online and work with others.

For more, see the official [Git Book](https://git-scm.com/book/en/v2).
