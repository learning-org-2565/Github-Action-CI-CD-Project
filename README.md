discription , we can put info here  
git config --global --edit ----> change the name or email. to comeback ==  :wq!+entr

If you made chnages in the remote repo, then execute this command to be updated
git pull origin main

git add . && git commit -m "created new branch to test PR EVENT  " && git push origin -u main

When you made changes in UI GITHUB Directly we have to run below command in the local CMD to make it clear ,up to date.

git pull origin main

To create branch
git checkout -b <branch name>
To switch to the branch  
git checkout <branch name>

npm run start #to test NPM is working or not

By defualt source code of repo is not available for the workflow for that we need to add a step called checkout.

Added event trigger code whenver we raise new pr with main branch then only actions will trigger...
