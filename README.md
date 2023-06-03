# Git

```sh
/ # which git
/usr/bin/git
/ # git --version
git version 2.40.1
/ # git config --global user.name "Pon Jagannath"
/ # 
```

```
/ # git config --global user.email = "ponskillhub@gmail.com"
```

```
/ # git config --global user.email "ponskillhub@gmail.com"
```

```
root@09ae4c2009ae:/# git config --list
user.name=Pon Jagannath
user.email==
```

### initialize git on a existing code

```
git init
```

### stop git from tracking a directory

```
rm -rf .git
```

### track status

```
git status
```

### git ignore

```
vi .gitignore
```

```
*.java
*.project
```

![GitStatus](gitStages.png)

```
git status
```

### Add files to staging area

```
git add .gitignore
```

```
git add -A
```

### Remove a file from staging area

```
git reset .gitignore
```

### remove all files from staging area

```
git reset
```

### Commit code

```
git commit -m "Initial Commit"
```

### git log

```
root@09ae4c2009ae:/Local-Repo# git log
commit 92cd9f9dbaa8ab692f63bd04d3c3b3f910cbd2b1 (HEAD -> master)
Author: Pon Jagannath <=>
Date:   Sat Jun 3 04:40:33 2023 +0000

    Initial Commit
```

### git clone

```
git clone ../Remote-Repo/.git .
```

### View info about the remote repo

```
root@09ae4c2009ae://Cloned-Repo# git remote -v
origin  //Cloned-Repo/../Remote-Repo/.git (fetch)
origin  //Cloned-Repo/../Remote-Repo/.git (push)
```

```
root@09ae4c2009ae://Cloned-Repo# git branch -a
* master
  remotes/origin/HEAD -> origin/master
  remotes/origin/master
```



