### How and When Conflicts Ocuur
    When integrating Commits from a different sources conflicts are occur

    When?
        1. git merge
        2. git rebase
        3. git pull
        4. git cherry-pick
        5. git stash apply

git most of the time decide which code should be add, but some situations need which code should be used that kind of situations git show us a conflict.

### merge changes to main branch
`git merge <branch-name>`


### Undo a conflict and start over
can be undone even you are at the dead end
`git merge --abort`

### how conflict look like  
``` 
<<<<<< HEAD  
    current code   
======  
    from the branch that need to merge  
>>>>>> develop

```

