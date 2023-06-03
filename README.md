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
