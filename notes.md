## Basics
* Git will have projects, repos/repository
* group of repos is called project
* Repos in git
    * local repo: repo in local machine
    * remote repo: repo in github.com
    * local repo changes has to be pushed to remote repo for changes to reflect in remote repo

## Git push steps
* Making local repo changed files ready to commit
```
git add *
git add fileName.extension
git add fileName.extension, fileName.extension
```
* commit the files local repo
```
git commit -m "commit message"
```
* Push committed changes from local repo to remote repo
```
git push
```

## Branches
* Default branch for any repo - `master`
* we will create multiple branches for development
* branch types
    * master
    * develop
    * release
    * feature
    * hotfix
* we create develop branch from master
* we create release branche(s) from develop
* all release branches merges to develop
* develop branch merges to master
* master get deployed to production