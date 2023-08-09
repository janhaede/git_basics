# git_basics

Git Basics and how to use them

Setup

1. Setup SSH connection
   1.1 Create SSH keypair on local machine
   1.2 Start SSH agent
   1.3 Add SSH keypair to agent
   1.4 Copy content of key file to the github menu to add it to your account
2. Create repository
3. Clone repository to local machine using ssh
   - "git clone @repository"

Commits

1. Add your changes to the staging area
   - "git add \* (all files)"
   - "git add filename"
     Optional: Check changes with "git status"
2. Commit all staged changes and add a message
   - "git commit -m message"
