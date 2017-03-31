# Git

## create a new repository on the command line 
```bash
$ echo "# note" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin repo_url.git
$ git push -u origin master
```

##  push an existing repository from the command line
```bash
$ git remote add origin repo_url.git
$ git push -u origin master
```

## create new branch
```bash
$ git checkout -b new_branch_name 
Switch to a new branch "new_branch_name"
```
This is shorthand for:
```bash
$ git branch new_branch_name
$ git checkout new_branch_name
```
