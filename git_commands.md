# How to delete a file on Git

git rm <file>
git commit -m "Deleted the file from the git repository"
git push

Something that worked for me was to use the -f flag following the git add command. This will force the file to be added to the repository. Then you can use the git rm command to remove the file from the repositor:

git rm -f git_commands.txt

Note: "git rm" delete files from repository and filesystem

# How to see what is about to be committed

git diff --cached

# To create a new branch named "experimental", use

git branch experimental

or you can use 

git reset HEAD <file>...

# Git status to see what is going on in the repository

git status

# How to see the history of commits

git log

# How to undo a git add command (unstage a file)

git restore --staged <file>...

# Adding all files to the staging area

git add .