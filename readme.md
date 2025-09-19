## basic git commands
## 1. git init - To initialize a repository or to start tracking all files in a folder
## 2. git status - Gives you the status or more info about your repository
## 3. git add - Will tell git what files to track e.g git add index.html
## 4. git add . - Tracks all files
## 5. git rm - This will remove a file from being tracked and also delete the file
## 6. git rm --cached [file_name] - This will remove a file from being tracked, but the file will still be on your system
## 7. git commit -m 'first commit' - This creates a commit i.e a snapshot of a particular version of your code

<!-- once you have staged your files, you can commit them into Git. Imagine a commit command as a save progress of your work at a certain point. A commit is a save point for your project. Just like saving your game before fighting the boss — if things go wrong, you can reload that save. In Git, if your code breaks, you can go back to an earlier commit where everything worked fine. You assign a commit message to every commit, which you can pass with the -m prefix -->

A - Added/Tracked: A file which has been previously staged or commited
U - Untracked: A file which has not being staged or commited
Ignored - A file which git has been explicitly told to ignore
M - (Modified)

<!-- Configure git -->
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL"
you can only configure once