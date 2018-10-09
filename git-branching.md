# Git Branching

Find more at the interactive tutorial at [https://learngitbranching.js.org/](https://learngitbranching.js.org/)

## Commits

`git commit` - a snapshot of all the files a directory. Git maintains a lightweight commit history by only saving a compressed version of the _changed_ files between commits.

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





