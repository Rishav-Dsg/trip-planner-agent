##### Github commands #####

## git config ##

``` git config --global user.name "Your Name" ```
``` git config --global user.email "your_email@example.com" ```
``` git config --global --list ```

## create repo + check status + add files + commit changes ##

``` git init```
``` git status ```
``` -> git add . ```
``` -> git commit -m "your message" ```

## connect local repo to github ##

``` => git remote add origin https://github.com/USERNAME/REPO.git ```
``` git remote -v ```

## push code to github ##

``` => git branch -M main ```
``` => git push -u origin main ```
``` -> git push (later pushes)```

## pull latest changes from github + clone existing repo##

``` git pull origin main ```
``` git pull -u origin main --allow-unrelated-histories ```
``` git clone https://github.com/USERNAME/REPO.git ```

## view commit history ##

``` git log (--oneline - shorter version)```

## create + switch + delete +see all branch 

``` git checkout -b feature-name ```
``` git checkout main ```
``` git branch ```
``` git branch -d branch-name ```

## undo changes before commit + remove file from git tracking ##

``` git checkout -- filename.py```
``` git restore . ```
``` git rm filename.py ```

## save work temporarily ##
``` git stash ```
