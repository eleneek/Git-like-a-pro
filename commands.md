## Branching
git branch
git branch -a

## Fetching
git fetch --prune

## Stashing
git stash
git stash push -m "message"
git stash list
git stash apply
git stash apply stash@{2}
git stash pop stash@{1}
git stash clear

## Cherry-pick
git cherry-pick <commit-hash>

## Reset / Revert
git reset --soft commit hash
git reset HEAD~N
git reset --hard commit hash
git revert commit hash

## Biscet
git bisect start
git bisect bad
git bisect good <commit name>
git bisect reset

## Remove cached
git rm --cached filename
