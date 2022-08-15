# Git Command

## Configuration Level
### Local configuration
```
git config --local user.name "PisitRujirojananon"
git config --local user.email "pisit.rujirojananon@allianz.com"
```
### Global configuration
```
git config --global core.editor "code --new-window --wait"
```
### System configuration
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

## Git Show
```
git show id(commit id)
git show HEAD
git show HEAD^
git show HEAD^^^^
git show HEAD~4
```

## Git blame
```
git blame Readme.md
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

## Git Remove(git rm)
```
git rm <filename>
git rm --cached <filename>
```

## Git Diff(git diff)
```
git diff (compare between workspace and index)
git diff --cached (compare between index and local repository)
git diff id..id2
git diff HEAD..HEAD~3 (Move Back)
git diff HEAD~5..HEAD (Move Forward)
```
