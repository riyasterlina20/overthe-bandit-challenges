# Bandit level 21 - >22

## Objective
to retrive the password from the cron
## Commands Used
ls /etc/cron.d/,cat /etc/cron.d/cronjob_bandit22,cat /usr/bin/cronjob_bandit22.sh,cat /tmp/t7061ds9S0RqQh9aMcz6ShpAoZKF7fgv
## Explanation
we need to run ls /etc/cron.d/ to see the task that are scheduled and then use thiscommand cat /etc/cron.d/cronjob_bandit22 to see the script and then this command cat /usr/bin/cronjob_bandit22.sh to see the file where the password of bandit22 is being written
## Outcomes
learned what is cron how it does its job
flag:tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q
