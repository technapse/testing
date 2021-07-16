git --version
git config --global user.name "Amit Gulati"
git config --global user.email "amit.gulati@gmail.com"
git config --global core.editor "nano -w"
git config --global core.editor "code --wait"
git config --list

git init
git clone
git status
git add <file name> // add file to staging area
git commit -m "Commit message" //commit the file to repository
git log //shows the log of all the commits in reverse chronological order
git log --oneline //shows log os all commits with single line summary
git diff //compare current uncommitted state with last git state
git diff --staged //runs a diff between the staging area and last known git state
git diff HEAD~<Number> //compare HED with commit <number> ago
git diff <Hash>


