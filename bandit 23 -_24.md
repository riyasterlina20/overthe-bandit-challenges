# Bandit level 23 ->24

## Objective
to write script to obtain the password for the bandit24
## Commands Used
ls /etc/cron.d/,cat /etc/cron.d/cronjob_bandit24,cat /usr/bin/cronjob_bandit24.sh,nano pass.sh,chmod +x pass.sh,cp pass.sh /var/spool/bandit24/foo/pass.sh,cat /tmp/bandit24_pass
## Explanation
first we need to use this command ls /etc/cron.d/ to see the cron job diectory then cat /etc/cron.d/cronjob_bandit24 executes this command after followed by this command cat /usr/bin/cronjob_bandit24.sh and then you will see the message what the cron doing and then create the file nano pass.sh and paste script(#!/bin/bash
cat /etc/bandit_pass/bandit24 > /tmp/bandit24_pass) and then change the file to executable using chmod +x pass.sh and then copy the file to the diectory where the cron executing the script using the command cp pass.sh /var/spool/bandit24/foo/pass.sh and then finally execute the file command to see the password
## Outcomes
learned how cron works and how to create script
flag:gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8
