# HowToUseGit
[How to](https://help.github.com/categories/writing-on-github/) edit .md files!

## GIT COMMAND
```
git add <filename> - to add file to stage changes, to add all files type: "git add ."

git status [-s] - to check status of your branch. [-s] for short version.

git commit [-m] "commit text" - to commit files, you can commit files separately by step: git add <filename> then git commint [-m] "filename A changes" and then second add's command.

git log - to see project history

git branch [-d] <branchname> - to add new branch or delete existing branch

git checkout <branchname> - to change current branch

git clean [-n] [-f] - remove untracked files from working dir. [-n] for dry run. [-f] for force.+

git clone <https://github.com/Inflanty/HowToUseGit.git>

git show-branch

git push - to upload traced files into online repo

git push --set-upstream origin feature/devTeam-0001

git merge origin/<branchname> - to update local branch witch other

git tag <tagname> - to create tag for last commit

git tag - to see all tags

git revert HEAD - to cancel the commit
```


### Branch
Pull request - when some branches wants to push files into master branch then ceating new pull request.

In big projects we have :

purpose | branch #0 | branch #1 | branch #2
----------|----------|---------|---------
3 state branching for develop | master(customer) | epic(feature) | feature/developer team
3 state branching for support | master(customer) | epic(release) | release/bugfix

### Version
You can use git's version for specify version of defined commit.
