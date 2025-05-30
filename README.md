git init: initialize current folder as a git respository
git clone <URL>: brings the git repo from <URL> to current folder
git status:  what you need to know about respository
git add <FILE"  : adds file to the staging area
git commit :  open a text editor to write commit message
git log: shows th log (history of our commits
  or git log --oneline : shows the shorter oneline commit


git  diff : compare current uncommitted state with last known git state
git diff HEAD~1 :compares HEAD with commit <number> ago (relative)

git diff --STAGED : runs git diff between the staging area and the last known state
git diff <HASH): compares HEAD with the commit <HASH>

