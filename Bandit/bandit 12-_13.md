# Bandit level 12 ->13

## Objective
to find the password in data.txt which is hexdump file repetedly compressed
## Commands Used
tar, gzip, bzip2, xxd, mkdir, cp, mv, file
## Explanation
we need to move the data.txt to another tmp directory for that we should use cp ~/data.txt . and then reverse the hexdump using this command xxd -r data.txt > jack and then see the file type using file command if it is gzip use gunzip to decompress else if it is bzip2 use bunzip2 to decompress else if it is tar use tar -xf jack
use this in loop untill you see text file
## outcomes
learned hoew to use the commnads mentioned above
flag:FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
