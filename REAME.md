## Compass Playground Team 01 David

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
