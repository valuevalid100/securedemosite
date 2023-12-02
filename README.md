# initialize git to this dir

git init

# change branch master to main

git branch -M main

# git file add

git add README.md

# git commit to local repo

git commit -m "First Commit"

# ssh generation using git bash from start menu

ssh-keygen -o

# some .pub file will have key under .ssh dir

-- copy and add that to git remote repo

# git link remote repo to local repo by copy ssh url from remote repo

git remote add orgin $copied_remote_ssh_url

# push changes to remote repo

git push origin main

# added tag

git tag -a v1.0 "1st Release"

# push with tag to remote repo

git push origin v1.0

# create branch1 and swtich to branch1

git checkout -b branch1
