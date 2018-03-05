# presentation
https://enucatl-presentations.github.io/2018.03.06.progress.report/

git hook to push the compiled version to gh-pages
-------------------------------------------------
```
ln -s ../../pre-push .git/hooks/pre-push 
```

git subtree remotes
-------------------
add
```
git remote add eth-reveal-theme git@github.com:enucatl-presentations/eth-reveal-theme.git
```

push
```
git subtree push --prefix=source/vendor/eth-reveal-theme eth-reveal-theme master
```
