# Bandit level 22 -> 23

## Objective
to find the password from the file in which the file name is hashed
## Commands Used
ls /etc/cron.d/,cat /etc/cron.d/cronjob_bandit23,cat /usr/bin/cronjob_bandit23.sh,echo I am user bandit23 | md5sum | cut -d ' ' -f 1,cat /tmp/8ca319486bfbbc3663ea0fbe81326349
## Explanation 
first we need to run ls /etc/cron.d/ to see the files listed for cron from there run this command cat /etc/cron.d/cronjob_bandit23 to see the script that cron running and then run echo I am user bandit23 | md5sum | cut -d ' ' -f 1 to see the name of the file which is hashed and then run cat /tmp/8ca319486bfbbc3663ea0fbe81326349 to see the password
## Outcomes
learned how cron and hash works
flag:0Zf11ioIjMVN551jX3CmStKLYqjk54Ga
