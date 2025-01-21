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

---

## 📝 Notes
- Always use descriptive commit messages.
- Ensure you pull updates before making changes to avoid conflicts.
- This repository will grow as more commands and concepts are learned in the course.

Happy coding! 😄

