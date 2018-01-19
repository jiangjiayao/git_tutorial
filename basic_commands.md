# basics
```
git --version
git config --global

git help [action] -> git help config
git [action] --help -> git config --help
```
# new project from local machine
```
git init [project_name] -> project_name optional

```

# download project from github
```
git clone [__url__] [local_path]

git remote -v
git branch -a

```

# push updates to github
```
git diff

git status

git add [file_names]
git add -A -> add all files staging area

git reset [file_name]
git reset -> remove everything form staging area

git commit -m "detailed message"
git log

git pull origin master
git push origin master
```

# start to work on branches
```
git branch [branch_name]
git checkout [branch_name]

git branch -> list all branches on machine, * on working branch

git push -u origin [branch_name]
```

# merge branches to master
```
git checkout master

git pull origin master
git branch --merged -> branches merged so far

git merge [branch_name]
git push origin master
```

# delete branches
```
git branch -d [branch_name] -> remove branches on machine

git push origin --delete [branch_name] -> remove branches on github
```
