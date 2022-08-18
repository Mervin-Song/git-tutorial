# git-tutorial -> The header
Demo

## git-status and git-add

.git folder is hidden and stores all the changes made to our code when we save it.

When we create a new file, and use the command 'git status', it will show the newly created file as an untracked file.

In order to add the file to be tracked we need to use 'git add', 'git add .' tells git to track all the listed files that have been created, modified or changed.

## git-commit
'git-commit -m' tells git to commit the file changes and append a message to it. The message should say why we commit.
we can add a second -m ('git-commit -m' "Added index.html" -m "description here") to insert a messsage to the description box

## git-push 
push it to a remote repository where our project is hosted. I assume its in git-tutorial folder in my github repository

## generating test-key SSH
testkey => Private SSH key only for u | Keep secure on local machine
=> Use the private key to show  
testkey.pub => Public SSH key and can be seen by everyone (starts with ssh-rsa and ends with our email)
ssh agent service (?)

## git push origin master
origin stands for the location of our git repository
master stands for the branch that we want to push to.
E.g. git push origin dev => push to the dev branch

## git init
To initialize a file and make it into an empty git repository

## git remote add origin <HTTPSLINK>
When a new folder is created OUTSIDE of the original cloned repo from github, it wont be automatically connected to github. We need to use the above code to add it

## git pull 'branch name'
Make sure to always run git pull 'branch name' as a habit in order to pull the latest update from dev branch or something.

