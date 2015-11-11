# Como atualizar um repositório forkado

```
git remote add upstream https://github.com/whoever/whatever.git

git fetch upstream

git checkout master

git rebase upstream/master

git push -f origin master
```

[Fonte](http://stackoverflow.com/questions/7244321/how-to-update-a-github-forked-repository)