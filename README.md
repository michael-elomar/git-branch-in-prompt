# git-branch-in-prompt
A script to add git branch name in terminal prompt

1. ```source git-prompt.sh```
2. ```GIT_PS1_SHOWDIRTYSTATE=true```
3. ```export PS1='\[\033[01;32m\]\u@\h\[\033[00m\]\[\033[01;34m\]\w\[\033[01;33m\]$(__git_ps1 "(%s)")\[\033[00m\]$ '```
