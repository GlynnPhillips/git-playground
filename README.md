# git-playground
Somewhere to try out new git commands without the fear of breaking things


## Notes / Commands to talk about

### git add -p (--patch)

### git cherry-pick

### git creating and apply a patch

### Create a patch for changes that have not been added

`git diff > changes.patch`

### Apply a patch from a `.patch` file 

`git apply < changes.patch`

### Undo latest commit

Keep changes locally -> `git reset --soft HEAD~1`
Remove changes locally -> `git reset --hard HEAD~1`

	

