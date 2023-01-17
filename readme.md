# commands related to git brancing


## show git branches
`git branch`

## create a new branch
`$ git branch <new-branch>`

## switching branch
`$ git checkout new-branch`
`$ git switch main`

## rename the current branch
`$ git branch -m <branch-name>`

## rename seperate branch not the current branch
`$ git branch -m <current-branch-name> <new-branch-name>`

## publich local branch into remote repository
`git push -u origin <branch-name>`

## delete a fully merged branch
`git branch --delete <branch-name>`

## delete a not fully merged branch
`git branch -D <branch-name>`

## get remote branch to local
`git branch --track <local-branch> origin/<remote-branch>` 
