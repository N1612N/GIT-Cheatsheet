## Push Local Repository to GitHub

```sh
git remote add origin <GIT URL: https://github.com/N1612N/Repo-name.git>

# push our master branch to the origin url, and set it as the default remote branch
git push --set-upstream origin master
# you will get some kind of notification you to authenticate this connection if connecting for first time.
```

## Pull Changes from GitHub
```sh
# git pull = fetch + merge
git pull <origin>
```

## Push Changes to GitHub
```sh
git commit -a -m "Change message"
git push <origin>
```