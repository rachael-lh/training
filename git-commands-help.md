To clone a repository from remote

# git clone <name of the remote repository>

git clone https://github.com/JitenPalaparthi/training.git 

# Local and Remote are two different repositories because git is distributed version control system

# To check branch(es)

git branch

# create a branch

# git branch <name of the branch>

git branch feature1

git checkout feature1

# Another way of create and checkout to the branch 

# git checkout -b <branch name>

# git checkout -b feature1

# After making changes , add or delete files the first step is to stage them

# To stage 

# git add <name of the file(s)>

git add go.mod main.go

# To Commit

# git commit -m <some message in simple present tense>

git commit -m "Add go based project"

# To push to remote

git push origin feature1

# git fetch : It is used to headers from the remote

git fetch origin main

# Merging from your remote to local

git pull origin main

