git init
git status
git add . or git add file_name
git commit -am "message" or gir commit -am 'message' ((add and commit)if file already exists and)
git log (show all commits list)
git push -U origin main
git pull

git branch (show all branches and display current branch)
git branch "branch name" (create a new branch)
git branch -m "new branch name" (you must be in branch that you want rename)
git branch -D "branch name" (delete branch)

git checkout "branch name" (change between branches)
git checkout -b "branch name" (create and change to new branch)

git merge "branch name" (you must be in the main branch to run this command)

git remote add origin "github repository url"
git remote set-url origin "your user @ github url repository" https://yourGitHubUser@github.com/george-mathias/github-actions-teste.git
- you must generate a individual token on github/settings/developer settings/tokens(new personal access token)


git remote get-url origin (it returns remote repository url)