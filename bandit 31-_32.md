# Bandit level 31 ->32 

## Objective
to retrive the password from the git repo
## Commands Used
git clone ssh://bandit31-git@bandit.labs.overthewire.org:2220/home/bandit31-git/repo,cat README.md,echo "May I come in?" > key.txt,git add -f key.txt,git commit -m "Add key.txt",git push
## Explanation
first we need to clone the repo and then read the README.md file and then yiu canb see that it is saying the file,content and branch the gitinore blocks the txt file we need to create the key.txt file and write the content using the command echo "May I come in?" > key.txt and force add the file using thsi command git add -f key.txt and then use this command commit -m "Add key.txt" finallly push the git with this command it will reveal the password git push
## Outcomes
learned how to push the file in remote repo
flag:3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K


