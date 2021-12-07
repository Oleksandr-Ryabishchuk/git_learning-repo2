# Test repository created on local machine

+ Description

Turning the folder to git repository:
- git init 

Create a new repository in github and use command:
- git remote add origin https://github.com/Oleksandr-Ryabishchuk/git_learning-repo2.git

Check remote repo by:
- git remote -v 

It's possible to make origin default by typing push like this:
- git push -u origin master

## Branches

- check branches: git branch
- create new branch: git checkout -b featured_readme
- switch branches: git checkout main

# Check the difference between branches by: 
- git diff featured_readme

# Get changes from merged branch tolocal code: 
- git pull or git pull origin master (if not changed to master branch)

# To delete branch: 
- git branch -d featured_readme

# In case if we modified some file we can use a shortcut for add and commit simultaneously:
- git commit -am "goes president"