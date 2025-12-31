# Bandit level 20 -> 21

## Objective
to find the password we need to make a connection using nc
## Commands Used
nc -l 5555,./suconnect 5555
## Explanation
first we need to ls to to see the file ls -l to see the permission it will have setuid permission we need to make connection using command in one terminal nc -l 5555 and in another terminal run this commmand bandit user ./suconnect 5555 and type the password in the nc and you will receive the password from the bandit21 file
## Outcomes
learned how to make connection using netcat
flag:EeoULMCra2q0dSkYj561DX7s1CpBuOBt
