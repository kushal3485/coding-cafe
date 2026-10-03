Q1: --global applies these settings to all Git repositories for your current system user. Leaving it out sets the configuration only for the current repository.   
Q2: The .git folder appeared. It contains all tracking data, configuration, history, and version control metadata for the repository.   
Q3: Git lists untracked files/folders. .venv/ (or dependencies/build files) looks like something not manually written.   
Q4: .venv/ and other ignored items specified in .gitignore disappeared from the untracked list.   
Q5: Yes, .gitignore should be committed. It ensures everyone working on the project shares the same rules for ignored files.   
Q6: README.md moved from "Untracked files" (or "Changes not staged for commit") to "Changes to be committed". In the three-places model, it moved from the Working Directory to the Staging Area (Index).   
Q7: Git prints a summary showing the commit hash, branch (main/master), commit message, number of files changed, and insertions/deletions.   
Q8: The first seven characters are the short commit hash (SHA-1 checksum). They serve as a unique identifier for that specific commit.   
Q9: The four steps are: 1. Modify/Edit files, 2. Check status (git status), 3. Stage changes (git add), 4. Commit changes (git commit).   
Q10: README.md is automatically recognized by hosting platforms like GitHub to display as the main landing page and project overview documentation. 
