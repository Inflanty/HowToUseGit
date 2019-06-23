# HowToUseGit
[How to](https://help.github.com/categories/writing-on-github/) edit .md files!

Git is a Distributed Version Control (DVC) system - which mean that every single developer 
has own version of repository - locally. You as a developer, have own code server locally,
each information regard to the repository are stored in .git/ directory. Dev could paush/pull changes to 
the cloud which is only box for the code. Cloud service provide the way to communicate/cooperate
witch a rest of dev team. Which means that you can switching the branches beeing offline, it 
could be helpful but also dangerous, when you keep the code too long locally, witchout pushing it
or pulling the changes from the cloud.

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

git branch --set-upstream-to=origin/master - if you want to pull from master. Also you can run this : git checkout -b <branchname> <originbranch>

```


### Branches
Pull request - when some branches wants to push files into master branch then ceating new pull request.

In big projects we have :

purpose | branch #0 | branch #1 | branch #2
----------|----------|---------|---------
3 state branching for develop | master(customer) | epic(feature) | feature/developer team
3 state branching for support | master(customer) | epic(release) | release/bugfix

### Version
You can use git's version for specify version of defined commit.
