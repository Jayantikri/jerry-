# jerry-
scripts
cat > gitclone
```
first go in directory which is to push in git
```
if git is not installed (sudo apt install git)
```........>git clone <link>  (link from github site code section https link)
```
ls (to check folder is there or data)
```
....>git switch branch name (to change branch)       
```
....>git add . (to add all changes in directory)
```....>git status (to show all changes  and commits)
```
..>git commit -m "message"
```
..>git branch (to check branch)
```
...>for token (go to github profile ..> setting...>developer settings...>personal access token..>token(classic)>>.generate new token
```
>>>>copy token and save after generating
```
.....>git push (branch if you want)
```
..>give username
```
..>paste token 

# commands to push code to git without cloning the repository
```
ansible_wordpress/ # first chnage the directory
git init
git remote add origin https://github.com/PoonamKri7665/ansible.git # add repository name 
git checkout -b ansible_wordpress
git add .
git status
git commit -m "ansible_wordpress"
git commit -m "ansible/wordpress"
git config --global user.email "......@gmail.com"
git config --global user.name "PoonamKri"
git commit -m "ansible/wordpress"
git push origin ansible_wordpress # ansible _wordpress is branch name here
```  
# command to check push file size in human readable format   
```
git ls-tree -r --name-only HEAD | xargs -I {} git cat-file -s HEAD:{} | awk '{total += $1} END {mb = total / 1024 / 1024; printf "%.2f MB\n", mb}'
```
git log (to check logs)
```
git reset commit id  (to reset commits)
```
du -sh * (to check file size individually)

