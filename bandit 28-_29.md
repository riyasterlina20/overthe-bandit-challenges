# Bandit level 28 ->29

## Objective
similar to previous level the difference is the file in markdown format
## Commands Used
git clone ssh://bandit28-git@bandit.labs.overthewire.org:2220/home/bandit-28/repo,git log,git show xxxxxx
## Explanation
as i said in previous level you can do this level in local machine first clone the repo using this command git clone ssh://bandit28-git@bandit.labs.overthewire.org:2220/home/bandit-28/repo and then use git log to see the log and then you can see the recent commit then copy the recent commit id and use this command to see the password git show b5ed4b5a3499533c2611217c8780e8ead48609f6
## Outcomes
learned how git logs leads to leak
flag:4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7
