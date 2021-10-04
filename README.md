# learn-git
Create local repo
    git init
Put file to staged
    git add .
    git add <filename>
    git add *.c
Unstage
    git restore --staged <filename>
    git reset HEAD <filename>
touch .gitignore
    Example
        abc.tmp
        *.log
        build/Release
Commit
    git commit -m "First commit"
Commit history
    git log
    git log --oneline
Restore the file after modified at the last commit