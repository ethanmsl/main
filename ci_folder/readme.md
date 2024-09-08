first association
```zsh
git remote add conf git@github.com:ethanmsl/fake_ci.git
git fetch conf
git merge --allow-unrelated-histories conf/master
```

update
```zsh
git pull conf -v
```


