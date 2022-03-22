## Git Commands

# git init          initialises a folder as a VSC
# git add <file>    adds a file to the VSC index
# git add .         adds/updates all files to VSC
# git branch <branch> create s a branch (for a feature) 
# git branch        lists the branches
# git switch <branch> chenages current branch 
# git log           shows commit history (use --oneline for brevity)
# git diff <branch a> <branch b> to display differences 
# git diff <commit a> <commit b> to display differences
# git diff <branch x> display diferences bteween branch x and current branch 
# git diff --cached <file> display diferences between last committed 
# git clone <url git> to clone an existing repository to your local machine 
# git restore  <filea, fileb, etc>  will reverse (undo) the last git add
# git restore --staged <file(s)> will reverse (undo) the last commit
# git rm <file> removes a file from VSC scope. YOu will need to commit a rm. You can restore a file after a remove , only before you do coimmit it
# git rm -r <folder> to remove (with recursive deleteion) a folder
# git mv <file> to move file (or to rename files
# git branch -m <existing-branch> <new-name> This will rename a branch 
# git branch -m <new-name> will rename the current branch
# git remote -verbose displays information about the repository where it was cloned or forked 
# git commit this command commits a set of changes that have been add(ed) to a branch 
# git commit -ammend -m'<new message> to change the commit message 
# git push  to push local changes to the remote repository 
# git push --set-upstream origin <new-branch> to push and create a branch remotely (existing locally but not remote) 
