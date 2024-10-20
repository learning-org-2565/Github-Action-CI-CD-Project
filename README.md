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

Added event trigger code whenver we raise new pr with main branch then only actions will trigger.

=========
Context in the Github Actions is like a Monitoring agents .
They monitor all the things happening , and whenever you need you get by calling them  the workflow using ${{github.<v name>}} 

============
Env Variable:
It is like a access card for example you are an employee for one particular company, they have diff branches ,building , and departments , for each one building and department they should give one access card insted of that they can provide one centralized access card and they can put all the access related info , with ine card he can go wherever they give access, that onecard is called env value. we can you use it in multiple times , create onece, use it for all . 
