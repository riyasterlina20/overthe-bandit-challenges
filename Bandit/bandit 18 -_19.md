# Bandit level 18 -> 19

## Objective
to read the password for next level from the readme file
## Commands Used
ssh -p 2220 bandit18@bandit.labs.overthewire.org "cat readme"
## Explanation
when we log in normally like this ssh -p 2220 bandit18@bandit.labs.overthewire.org when we entered the password it will kick us out because someone modified .bashrc file so it does not provide interactive shell so we need to run thic command to read the password for next level using this command ssh -p 2220 bandit18@bandit.labs.overthewire.org "cat readme"
## Outcomes
learned how to deal with non interactive shell
flag:cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
