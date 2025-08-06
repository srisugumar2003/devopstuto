# 💻 Git Commands Lab Report

## 🔧 Lab Setup

```bash
mkdir git-lab
cd git-lab
git init
touch file1.txt file2.txt
```

## 🅰️ Exercise Set A: Basic Git Commands

### 1. Initialize a Repository

```bash
git init
ls -a .git
```

**✅ Observation:** `.git` folder contains HEAD, config, hooks/, info/, objects/, refs/ etc.

### 2. Check Repository Status

```bash
echo "Hello Git" > file1.txt
git status
```

**✅ Observation:** file1.txt is shown as "modified".

### 3. Stage Files

```bash
git add .
git status
```

**✅ Observation:** file1.txt is now in staging (green color).

### 4. Commit Changes

```bash
git commit -m "Initial commit"
git log
```

**✅ Observation:** Shows commit hash, author, date, and message "Initial commit".

## 📋 Lab Execution Log

### Step 1: Repository Initialization
- Created git-lab directory
- Initialized Git repository
- Created test files (file1.txt, file2.txt)

### Step 2: Basic Git Operations
- Added content to file1.txt
- Staged changes
- Committed initial changes
- Verified commit history

## 🎯 Learning Objectives

1. **Repository Management**
   - Initialize Git repositories
   - Understand Git directory structure
   - Navigate Git workspace

2. **File Operations**
   - Create and modify files
   - Stage changes for commit
   - Commit changes with meaningful messages

3. **Status Monitoring**
   - Check repository status
   - Understand file states (untracked, modified, staged)
   - View commit history

## 📊 Expected Outcomes

After completing this lab, students should be able to:
- Initialize a Git repository
- Create and modify files
- Stage changes using `git add`
- Commit changes with descriptive messages
- Check repository status and history
- Understand basic Git workflow

## 🔍 Key Concepts Covered

- **Git Repository**: A directory containing project files and Git metadata
- **Staging Area**: Intermediate area where changes are prepared for commit
- **Commit**: A snapshot of the repository at a specific point in time
- **Working Directory**: The directory where you make changes to files
- **Git Status**: Command to check the state of files in the repository

## 📝 Notes

- Always use descriptive commit messages
- Check status frequently to understand file states
- The `.git` directory contains all repository metadata
- Git tracks changes, not files directly 