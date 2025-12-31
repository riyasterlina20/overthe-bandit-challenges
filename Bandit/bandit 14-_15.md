# Bandit level 14 -> 15

## Objective
to find the password to next level by netcat
## commands Used
cat /etc/bandit_pass/bandit14,
nc localhost 30000
## Explanation
we need to first see the password by using the command cat /etc/bandit_pass/bandit14 and then use nc localhost 30000 this to establish the connection and send the password and then you will receive the password for the next level
## Outcomes
learned how to use netcat to establish connection
flag:8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
