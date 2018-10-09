# Git Branching

Find more at the interactive tutorial at [https://learngitbranching.js.org/](https://learngitbranching.js.org/)

### Commits

`git commit` - a snapshot of all the files a directory. Git maintains a lightweight commit history by only saving a compressed version of the _changed_ files between commits.

### HEAD

Head is the symbolic name of the currently checked out commit. It's what you're committing your current work on top of.

You can change HEAD by checking out a different commit using `git checkout e2o1i` where `e2o1i` is the first few characters of the commit you're going for.

# Branching

Create a branch with

`git branch <branch-name>`

Checkout with

`git checkout <branch-name>`

Or create a branch and checkout the new branch with

`git checkout -b <branch-name>`

# Merging

Merge two branches together with

```
git checkout master
git merge <feature-branch>
```

![](https://developer.atlassian.com/blog/2014/12/pull-request-merge-strategies-the-great-debate/what-is-a-merge.gif)

# Rebasing

Rebasing is another way of combining work between commits. Rebasing takes a set of commits, "copies" them, and plops them down somewhere else.

Do work on two different branches

```
git checkout -b feature && git commit 
git checkout master && git commit
```

Replay one commit on top of the other

```
git checkout feature
git rebase master
```

![](https://cdn-images-1.medium.com/max/1600/1*W-soT3vkC9VfCacHLl75bA.gif)

# Moving around branches 

`git branch -f <branch> <commit-hash>`

# Reversing Changes 

Reversing changes in git has both a low-level component \(staging individual chunks\) and a high-level component \(how the changes are actually reversed\). 

There are two ways to undo changes in Git: 

1. `git reset` - moves a commit back as if it never happened, but doesn't share those changes with remote branches. 
2. `git revert `- creates a new commit that is identical to a previous commit, so that it can be pushed.

# Git Cherry-pick

A straightforward way of copying a series of commits below your current location \(HEAD\). 

```
git cherry-pick <commit1> <commit2> <...>
```

Basically, it just grabs the changes made in the commit's you've named and commits them again under you. Tricky, but not complicated - you just need to know the hashes corresponding to the commits you want to include. 

# Git Interactive Rebase 

Interactively choose, omit, reorder, or squash commits in an interactive rebase. 

For example, to interactively choose from the four levels below HEAD:

```
git rebase i HEAD~4
```





