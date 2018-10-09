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

