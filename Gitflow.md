Create Github organization.
Add all members and make them owners. 

Develop on branch. You will ONLY code on your branch. NEVER code on the master branch. Coding on the master branch eliminates the process of merging, which is where you will catch conflicts between what you had (existing/working product) and what you're adding (features containing potentially breaking code).
  - git checkout -b "branchname" (make new branch)
  - git checkout "branch name" (switch to existing branch)
Checkout to master
  - git checkout master (switches to master branch)
Pull origin master (pulls down current master version from Github. This is important because you need to make sure you're merging the most updated version of your product with what you've been coding on your branch so that you can find and resolve all potential conflicts).
  - git pull origin master 
Checkout to branch. You are now back on your development branch.
  - git checkout "branchname"
Git merge master. This is where you combine the master branch with your development branch (production code). 
  - git merge master
Accept current/master/both. If there are conflicts between the code of your branch and the master branch, it will display them when you try to merge. You will have to accept the master version, the branch version, or both to Complete the merge. Your branch now reflects the master with the changes from your development branch.
Add/commit. 
  - git add .
  - git commit -m "some commit message"
Push from your branch. You are updating the version of your branch on Github to be the merged code you just created.
  - git push origin "branch name"
Create a pull request on Github. Github will recognize that your branch is now different from the master, and give you the option to make a pull request. You will then let your group lead (staff member) know and they will approve and merge the PR. 

Congratulations! Your master now contains your new features!