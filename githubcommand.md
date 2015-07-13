**Combining the Git Command Line with the Github Workflow**

*Prerequisite:*
Clone a repository from Github:  
`git clone therepositoryname`

**Workflow**

1. From within the repository's directory on your local machine, create a branch:  
`git branch thisisthenewbranchname`

2. Checkout the branch:  
`git checkout thisisthenewbranchname`

3. Make changes inside the branch (e.g., add code, add files, whatever)

4. Stage files and commit changes:  
`git add filename`  
`git commit -m "the commit message"`  

5. Send your local branch to github:  
`git push`  

6. Go through the pull request process on Github. Be sure to delete the Github (remote) branch manually after your pull request happens.

7. Delete the local branch. This first checks out the master branch with the intent to keep things straight when you later synchronize the remote Github version. When you delete the local branch, you might receive a warning message that your local changes have not been merged into master -- that is true. You'll add the updated Github  master in the next step:  
`git checkout master`  
`git branch -d thisisthenewbranchname`  

8. Update your local repository with the latest updates from Github's version:  
`git pull`
