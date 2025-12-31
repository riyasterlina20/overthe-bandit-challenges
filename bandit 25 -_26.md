# Bandit level 25 ->26

## Objective
to find the password by escaping from more
## Commands Used
ssh -i mathi bandit26@bandit.labs.overthewire.org -p 2220,:set shell=/bin/bash,:shell
## Explanation
first we need to know what is more it is the pager which will show you the text files and exits the ssh so we need to minimize the terminal screen as small as possible because more pause only when the screen is small so we force more to stop and press v to enter into the vi - text editor and then we need to shell to bash using the command :set shell=/bin/bash and then :shell to enter into the bandit26 and then we know where the password usually cat /etc/bandit_pass/bandit26 
## Outcomes 
learned about more and how it works
flag:s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ
