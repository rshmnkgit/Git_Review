### Display commit logs

**git log**

Displays detailed log

**git log --oneline**

Displays each log in a single line. Compact listing

**git log --oneline --graph**

The --graph option draws an ASCII graph representing the branch structure of the commit history.

### Undo Last Git Commit (with reset)

**$ git reset --soft HEAD~1**

“HEAD~1” means that you want to reset the HEAD (the last commit) to one commit before in the log history.

“–soft” tells Git not to modify the files in the working directory or in the index at all.

**$ git reset --hard HEAD~1**

Used to undo the last commit and discard all the changes in the working directory and index


