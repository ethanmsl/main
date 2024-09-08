git remote add conf https://github.com/ethanmal/fake-ci.git
git fetch conf
git merge --allow-unrelated-histories conf/master
