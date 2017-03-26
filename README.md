# CHI GIT CHEAT SHEET
## Feature Branch Example

```
// if using master, use that instead of develop
git checkout develop
git branch feature-task1
git checkout feature-task1

// make some changes

git add .
git commit -m "Changes..."

// when you're done with the feature
git push -u origin feature-task1

// pull any changes from develop
git pull origin develop
// merge develop into your feature-task1 branch
git merge --no-ff develop

// resolve conflicts, if any
// this may require git add & git commit

// switch back to develop and merge changes
git checkout develop
git merge --no-ff feature-task1
git push -u origin develop

// delete old branches
// ONLY after they have been merged
git branch -d feature-task1
```

## Other Commands
```
// list branch you are on
git branch

// list all branches
git branch -a

// 'soft' pull
git fetch

// show status
git status

```
