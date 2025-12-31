# Bandit level 13 ->14

## Objective
to find the ssh key to login in to the bandit14
## Commands Used
cp sshkey.private /tmp/bandit13key_file,chmod 600 /tmp/bandit13key_file,scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private ~/bandit13key,chmod 600 ~/bandit13key,ssh -i ~/bandit13key bandit14@bandit.labs.overthewire.org -p 2220
## Explanation
we need to first copy the file and to stote in another directory to modify the permission using chmod 600 /tmp/bandit13key_file and then exit the connection and download the file from bandit13 to local machine using scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private ~/bandit13key and then we need to login as bandit14 using the key
## Outcomes
learned how to login ssh with rsa key
