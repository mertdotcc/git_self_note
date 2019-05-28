# Git Reference Guide

`$ git log --oneline`<br>
`$ git log --stat`

`$ git log -p` to see the changes<br>
`$ git show`

`$ git log -p fdf5493`

`$ git add` add files from the working directory to the staging index

`$ git commit` take files from the staging index and save them in the repository

`$ git diff` displays the difference between two versions of a file

`$ git commit -m "Initial commit"`

`$ git diff`

`$ touch project.docx` creates a word file named project

`$ git tag -a v1.0`

`$ git log --decorate`

`$ git tag -d v1.0` to delete a tag

`$ git tag -a beta b552fa5` by default, we add tags to the last commit. but if we want to add a tag to a previous commit, we simply type the SHA of it.

`$ git branch` will list out the branches in a repository

`$ git branch sidebar` to create a branch named sidebar

`$ git checkout sidebar` to switch from the master branch to sidebar branch

`$ git branch -d sidebar` to delete a branch

`$ git checkout -b richards-branch-for-awesome-changes` If you provide the `-b` flag, you can create a branch and switch to it all in one command.

`$ git commit --amend` alter the most-recent commit

`$ git reset` erases commits 

***

## GitHub & Collaboration

`$ git remote` to manage remote repository

`$ git push` send changes to the remote

`$ git pull` retrieve updates from the remote 

`$ git shortlog`  A quick way that we can see how many commits each contributor has added to the repository 

`$ git shortlog -s -n`
