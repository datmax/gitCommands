# gitCommands

## to create a repo:
`git init <repository name>`

## to add a remote:
`git remote add <link to the remote>`

## to push changes to a remote:
```
 git add . 
 git commit -m "<message>"
 git push <local branch name> <remote branch name>  # usually it's git push origin master
```
## to get changes from remote(safe way):
```
# git stash and git stash pop is used to make a backup of local changes
git fetch
git stash
git pull
git stash pop
```
