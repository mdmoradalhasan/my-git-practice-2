THIS IS THE ADDED LINE JUST TO TEST

bash# Set your icommit name
git config --global user.name "Your Name"

# Set your commit email address
git config --global user.email "youremail@example.com"

# Enable helpful command line colorization
git config --global color.ui auto
Use code with caution.📦 Creating & Cloning RepositoriesStart a new project or copy an existing one:bash# Initialize a local Git repository in the current directory
git init

# Clone (download) a remote repository locally
git clone <repository-url>
Use code with caution.🔄 The Daily Workflow (Stage & Commit)Track, examine, and save your local modifications:bash# Show changed/untracked files in your working directory
git status

# Add a specific file to the staging area
git add <file-name>

# Add ALL changed and untracked files to staging
git add .

# Record staged snapshots into commit history (opens editor for message)
git commit

# Commit staged changes with an inline message
git commit -m "Your descriptive commit message"

# Shortcut to stage and commit all modified, tracked files at once
git commit -am "Your commit message"
Use code with caution.🌱 Branching & MergingIsolate feature development and safely integrate changes:Manage features and integrate updates using core branching commands:bash# List, create, switch, merge, or delete local branches
git branch
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git merge <branch-name>
git branch -d <branch-name>
Use code with caution.📤 Sharing & SynchronizingConnect and share code with remote platforms like GitHub or GitLab:bash# Configure remotes, fetch, pull, and push changes
git remote -v
git remote add origin <remote-url>
git fetch origin
git pull
git push origin <branch-name>
git push --set-upstream origin <branch-name>
Use code with caution.🔍 Inspection & HistoryReview your project's commit history and file alterations:bash# View logs and file differences
git log
git log --oneline
git diff
git diff --staged
Use code with caution.🩹 Undoing Mistakes & StashingSafely revert changes or temporarily shelve incomplete work:bash# Reset files, discard changes, revert commits, or use stash
git reset <file-name>
git checkout -- <file-name>
git revert <commit-id>
git stash
git stash apply
