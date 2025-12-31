# bandit level 29 -> 30

## Objectve
to find the password which is in the git repo
## Commands Used
git clone ssh://bandit29-git@bandit.labs.overthewire.org:2220/home/bandit29-git/repo,git branch -r,git show README.md
## Explanation
first we need to clone the repo with this command git clone ssh://bandit29-git@bandit.labs.overthewire.org:2220/home/bandit29-git/repo and cat the file it will show no password in production and will show the branch as dev to see the branch use this commnad git branch -r and go to that branch and use this command to see the pasword git show README.md
## Outcomes
learned what is branch in git
flag:qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL
