# Git Commands

## Initializing a Repository
- **Initialize a new Git repository**  
  git init

## File Operations
- **Create a new file**  
  touch <filename>

- **View file contents**  
  cat <filename>

## Staging and Unstaging Changes
- **Stage a file**  
  git add <filename>

- **Unstage a file**  
  git rm --cached <filename>

- **Stage multiple files**  
  git add <file1> <file2>

## Committing Changes
- **Commit with a message**  
  git commit -m "Your commit message"

## Checking Repository Status
- **Check the status of the repository**  
  git status

## Restoring and Removing Files
- **Restore a modified file to last committed state**  
  git restore <filename>

- **Remove a file from repository**  
  git rm <filename>

## Branching
- **Create a new branch**  
  git checkout -b <branch-name>

- **Switch to an existing branch**  
  git checkout <branch-name>

## Viewing Logs
- **View commit history**  
  git log

## Configuring User Information
- **Set global username**  
  git config --global user.name "Your Name"

- **Set global email**  
  git config --global user.email "your.email@example.com"

## Miscellaneous
- **Clear the terminal screen**  
  clear

- **Show history of commands**  
  history
