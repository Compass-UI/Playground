## Compass Playground Team 01 David

## Compass Playground Team 02
 
## Upload initial branch:
`git remote add origin https://github.com/Compass-UI/Playground.git`

### create a new repository on the command line


`echo "# Playground" >> README.md`

`git init`

`git add README.md`

`git commit -m "first commit"`

`git remote add origin https://github.com/Compass-UI/Playground.git`

`git push -u origin master`


### or push an existing repository from the command line


`git remote add origin https://github.com/Compass-UI/Playground.git`

`git push -u origin master`

### To push the current branch and set the remote as upstream, use

`git push --set-upstream origin master.Team01`

### Create your branch:

`git branch  master.Team01.David`

### set upstream branch

`$ git push --set-upstream master.Team01.David` 

### Open manual page to get help

`git push --help`

#### On Mac will print man page, on Windows will open the following page:
`file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-push.html`

### Push all local branches to remote

`git push --all`
![pull --all](/imgs/push-all.png)


### Merge conflicts

`gemini-david 🌴 : git push
To https://github.com/Compass-UI/Playground.git
 ! [rejected]        master.Team01.David -> master.Team01.David (fetch first)
error: failed to push some refs to 'https://github.com/Compass-UI/Playground.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
gemini-david 🌴 :`

## git reset HEAD

![git reset --hard HEAD](/imgs/hard-reset-head.png)

### I am resetting HEAD --hard <-- this should not be here>

### Default reset is --mixed

`git reset HEAD` is the same as `git reset HEAD --mixed`

## 4 Git Areas

1. Stash
2. Workspace
3. Staging/Index
4. Repository

## Git-flow
[Git-flow on github](https://github.com/nvie/gitflow)

![Create branch based on another](https://i.stack.imgur.com/6qEWk.jpg)

### Branch creation history visualization
![branch-creation-history-visualization.png](/imgs/branch-creation-history-visualization.png)
## How did I create my branch from Team02

`gemini-david 🌴 : git branch
  master
  master.Team01
* master.Team01.David
gemini-david 🌴 : pwd
/Users/v738110/Compass/Playground/Playground
gemini-david 🌴 : git branch
* Team02
  master
  master.Team01
  master.Team01.David
gemini-david 🌴 : git checkout -b Team02.John Team02
Switched to a new branch 'Team02.John'
gemini-david 🌴 :`

## This commit is done after Team02 did some more work on Team branch
