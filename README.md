how to setup git hub and start a repository;
Basic Commands

git init – Initialize a new Git repository
git clone <repo_url> – Clone an existing repository
git status – Check the status of your working directory
git add <file> – Stage a specific file
git add . – Stage all changes

Committing & Pushing

git commit -m "message" – Commit staged changes with a message
git push origin <branch> – Push commits to a remote branch
git push -u origin <branch> – Push and set upstream branch

Branching & Merging

git branch – List branches
git branch <branch-name> – Create a new branch
git checkout <branch> – Switch to a branch
git switch <branch> – (Newer alternative to checkout)
git merge <branch> – Merge a branch into the current one

Pulling & Fetching

git pull origin <branch> – Fetch and merge changes from a remote branch
git fetch – Fetch latest changes without merging

Undoing Changes

git reset <file> – Unstage a file
git reset --hard <commit> – Reset everything to a specific commit
git revert <commit> – Create a new commit that undoes a previous commit
