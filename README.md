# Git Commands - Scenario 1: Setting Up and Pushing First Code

This `README.md` provides a practical guide for setting up Git, managing code, and pushing it to a Bitbucket repository. The steps are simplified for easy understanding and use.

---

## 🚀 Quick Start

### 1️⃣ Configure Git
Set your name, email, and save credentials for future use:
```bash
# Set user information
git config --global user.name "John Smith"
git config --global user.email "john.smith@example.com"

# Store credentials
git config --global credential.helper store
```

### 2️⃣ Clone a Repository
Copy the repository URL from Bitbucket and clone it locally:
```bash
# Clone repository
git clone <repository-URL>

# Example
git clone https://bitbucket.org/johnsmith/my-first-repo.git
```

### 3️⃣ Check Repository Status
View the current state of your files:
```bash
# Check status
git status
```

### 4️⃣ Add Files
Add files to the staging area:
```bash
# Add specific file
git add <file-name>

# Add all files
git add .
```

### 5️⃣ Commit Changes
Save changes with a descriptive message:
```bash
# Commit changes
git commit -m "Your commit message"
```

### 6️⃣ Pull Updates
Fetch the latest changes from the remote repository:
```bash
# Pull latest changes
git pull origin main
```

### 7️⃣ Push Changes
Upload your changes to the remote repository:
```bash
# Push changes
git push origin main
```

### 8️⃣ Clean Up Untracked Files
Remove untracked files from the working directory:
```bash
# Remove untracked files
git clean -f

# Example output
Removing seeTest.txt.txt
```

### 9️⃣ View Commit History
View the history of commits in the repository:
```bash
# Show commit log
git log
```

### 🔟 Manage Branches
#### Create and Switch to a New Branch
Create a new branch and switch to it:
```bash
# Create and switch to a new branch
git checkout -b feature/profile

# Example output
Switched to a new branch 'feature/profile'
```

#### View All Branches
Check the current branch and list all branches:
```bash
# View branches
git branch

# Example output
* feature/profile
  master
```

#### Switch Between Branches
Switch back to the `master` branch:
```bash
# Switch to master branch
git checkout master

# Example output
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
```

Switch to the `feature/profile` branch:
```bash
# Switch back to feature/profile branch
git checkout feature/profile

# Example output
Switched to branch 'feature/profile'
```

---

## 📚 Command Reference

| Command                      | Description                                   |
|------------------------------|-----------------------------------------------|
| `git config --global`        | Configure user details and preferences       |
| `git clone <repository-URL>` | Clone a repository from Bitbucket            |
| `git status`                 | Check the status of files                    |
| `git add <file-name>`        | Stage a specific file for commit             |
| `git add .`                  | Stage all files for commit                   |
| `git commit -m "message"`    | Commit changes with a message                |
| `git pull origin main`       | Pull the latest changes from the main branch |
| `git push origin main`       | Push changes to the main branch              |
| `git clean -f`               | Remove untracked files from the directory    |
| `git log`                    | Show the commit history                      |
| `git checkout -b <branch>`   | Create and switch to a new branch            |
| `git branch`                 | View all branches                            |
| `git checkout <branch>`      | Switch to an existing branch                 |

---

## 📝 Notes
- Always use descriptive commit messages.
- Pull updates frequently to avoid conflicts.
- Use branching to manage features and keep the `master` branch clean.
- This repository will grow as more commands and concepts are learned in the course.

Happy coding! 😄

