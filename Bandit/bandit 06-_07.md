# Bandir level 6->7

## Objective
to see the password stored in the server
## commands used
cd /
find . -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
## Explanation
first we use cd / to see the root directory and use this command find . -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null to filter the file and you will see this./var/lib/dpkg/info/bandit7.password then use this command to cat /var/lib/dpkg/info/bandit7.password to read the password in the file
## Outcomes
learned how to filter file based on the requirement
flag:morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
