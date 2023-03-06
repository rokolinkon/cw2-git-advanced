# Git Advanced
## Welcome
Welcome to the sequel tutorial to Git Basics! This is a companion to the PowerPoint presentation which will go over actually _performing_ all of the Git operations gone over in that presentation. Everything from branching to stashing—we'll go over that here. Have the GitHub page for your forked repository open, because you'll be making a lot of changes both locally and remotely!

---

## Branching
### Creating branches
Create a new branch using `git checkout`—for this example, we'll call our new branch “first”: `git checkout -b first`<br>
Now, you can make all the changes you want on this branch without affecting the master branch until your changes are ready! How cool is that? You can use `git branch` to list all the branches you have, at which point you should now see `first` added to that list, with an asterisk next to it, indicating that `first` is your currently-selected branch.<br>To push this branch onto GitHub, use `git push --set-upstream origin first`.