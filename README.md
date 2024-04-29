# jerry-
scripts
cat > gitclone/n
```.....> first go in directory which is to push in git/n
```.......>if git is not installed (sudo apt install git)/n
```........>git clone <link>  (link from github site code section https link)/n
....>
```ls (to check folder is there or data)/n
```....>git switch branch name (to change branch)  /n     
```....>git add . (to add all changes in directory/n
```....>git status (to show all changes  and commits/n
```..>git commit -m "message"/n
```..>git branch (to check branch)/n
```...>for token (go to github profile ..> setting...>developer settings...>personal access token..>token(classic)>>.generate new token/n
```>>>>copy token and save after generating/n
```.....>git push (branch if you want)/n
```..>give username/n
```..>paste token /n
```>>>>
```>>>>
>>>>
>>>>#!/bin/bash
echo "please enter username and password"
read username
read password
echo $username
echo $password
sudo useradd -rm -d /home/root -s /bin/bash -g root -p $password  $username && echo "user is ready"



>>>>
