# how to post github repository in vs code file
- make a folder on desktop and open with vs code

- open terminal

- in terminal write git clone (link)

   git clone ourhttps;/link which is find in github code

- after pasting lik go github file using cd

    cd filename which is in github

- ls (to check list)

- git status (you can check github file status) 
    # status may be
  - untracked (new file gith yet not tracked)

  - modified (changed)

  - staged (file is ready to be committed)

  - unmodified (unchanged)

  ## Add and Commit
   -> add - adds new or changed files in your working directory to the Git staging area
      git add <-filename->
   
   -> commit - it is the record of chnage
      git commit -m "some msg"

 # Push command
   upload local repo (laptop,pc) content to remorte repo(github)
     git push origin main

## how to push your vs code folder to github repo?
   - go in terminal

   - if you are in another folder back outside of it using
      cd ..

   -  mkir folddername(eg.localRepo)   

   - if you want to skip upper 3 points you can simply create a new folder
        (eg.firstDemo)  desktop and create another folder in firstDemo (eg.localRepo)
        and countinue below steps

   -  make local repository using 
      git init

   - add and commit it in github using 
      git add <-filename->
      git commit -m "some msg"

   - go to the github and create a new repo (eg.localrepo)
      (we want to push my vs code in github localrepo)

   - git remote add origin <-link->
      (go and copy github repo file and paste in <-link->)
   
   - git remote -v
     (to verify remote)

   - git branch
     (to check branch)

   - git branch -M main 
      git(rename branch from mster to main)

   - git push origin main