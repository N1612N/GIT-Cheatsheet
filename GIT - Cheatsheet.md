## Configure Git

```sh
git config --global user.name "N1612N"
git congig --global user.email "nathanxoff@gmail.com"

# Use `global` to set the username and e-mail for **every repository** on your computer.
# If you want to set the username/e-mail for just the current repo, you can remove `global`
```

## Create a Folder and Initialize Git
```sh
mkdir Repo-name
cd Repo-name

git init
~ Initialized empty Git repository in /Users/user/Repo-name/.git/
```

## After files are created in the repository, Let's stage the files
```sh
# To check status
git status

# To add a Single file
git add filename.ext

# To add all files 
git add -all

```

# After files are stages, lets commit them
```sh
# commits are the savepoints

git commit -m "Message for commit"

# To commit without staging
git commit -a -m "Message"

```

## Git Logs
```sh
git log
```

## Git Branch
```sh
# To display all branches
git branch -a
# Current branch is where * is denoted.

# To add new branch
git branch <branchname>

# To change or switch to another branch
git checkout <destBranch>

# To display status 
git status

# To merge branch1 and branch2
# Move in to branch1, which is usually main branch.
git checkout branch1
# Merge now
git merge branch2

# To delete a branch
git branch -d <branchname>
```