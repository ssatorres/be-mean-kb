# Como atualizar um repositório forkado

```
git remote add upstream https://github.com/Webschool-io/be-mean-instagram.git

git fetch upstream

git checkout master

git merge upstream/master

git push -f origin master
```

Da segunda vez, não precisa dar o remote add upstream

[Fonte](http://stackoverflow.com/questions/7244321/how-to-update-a-github-forked-repository)