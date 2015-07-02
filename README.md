# git-cheatsheet
A cheatsheet for git

#Rebase
Rebase allows you to combine your commits together

```
git rebase <branch>
```

##Interactive Rebase

```
git rebase -i HEAD<num>
```
Examples
```
git rebase -i HEAD~3
git rebase -i HEAD^^^
```
