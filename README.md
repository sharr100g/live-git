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

git restore --source <hash> <file> restore file to hash or head
   -git checkout <hash or head> <file> -- restores file to <hash or head>
     ----- try to avoid the following ---
     - git checkout <hash or head>: if you forget the file, you end up in detached state
        then run this command either of the following commands to correct it:
        git checkout main : got back to main
        git switch main: go back to main

sharr@S-H-hpc MINGW64 /c/users/sharr/git/live-git (main)
$ git remote -v
origin  https://github.com/sharr100g/live-git.git (fetch)
origin  https://github.com/sharr100g/live-git.git (push)



