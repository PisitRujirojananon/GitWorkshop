# Git Config

## Configuration Level
### Local
```
git config --local user.name "PisitRujirojananon"
git config --local user.email "pisit.rujirojananon@allianz.com"
```
### Global
```
git config --global core.editor "code --new-window --wait"
```
### System
```
git config --system -e
```

## Git Log
### Filter
```
git log --since=1.day
git log --until=1.day
git log --grep="readme"
git log --author="Pisit"
git log Readme.md
```
### Format
```
git log -p (show detail)
git log --stat (show short detail)
git log --format=oneline
git log --oneline --graph --decorate
```

## Git ls-tree
```
git ls-tree HEAD
git ls-tree main
git ls-tree id (id from git log)
```

## Git add and commit
```
git add.
git add Readme.md
git commit -m "commit message"
git commit -am "add and commit"
git commit --amend
git commit --amend -m "commit and add new message"
git remote add origin URL (URL repository)
git remote -v
```