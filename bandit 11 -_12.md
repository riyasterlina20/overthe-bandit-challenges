# Bandit level 11 -> 12

## Objective
to find password by performing ROT-13
## Commands Used
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
## Explanation
we need to use cat to read and pass it through pipe to tr 'A-Za-z' 'N-ZA-Mn-za-m' to see the password
## Outcomes 
learned how to perform rot-13 using tr
flag:7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
