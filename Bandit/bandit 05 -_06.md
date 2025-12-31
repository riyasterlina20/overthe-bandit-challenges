# Bandit level 5 -> 6

## Objective
to see the password in the file which is not executable ,human readable and 1033 bytes of data
## Commnands Used
find inhere -type f -size 1033c ! -executable
## Explanation
in that we usede find command to find the file in the inhere directory and the type is file and size of 1033 characters finally not executable
## Outcomes
learned how to filter the output rather than brute forcing
flag:HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
