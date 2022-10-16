
# Git & Github:

Git: Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows. 

GitHub: GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.

# Git Commands Basic infrastructure :
![image](https://user-images.githubusercontent.com/54863241/196044560-d0c94417-7050-42d4-b038-7b45a71c6227.png)

# Git Commands :
________________________________________________
 ## 1) git init – This command  initializes the new working directory.
 ~~~bash
 git init
 ~~~
 ![image](https://user-images.githubusercontent.com/54863241/196044953-48dcd75e-3806-41cf-8627-57dc5620af3e.png)

 ## 2) git branch – Lists Branches in the repository
 ~~~bash
 git branch
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196045113-84752359-1345-4228-8809-28f2ea8ff2b2.png)
 
  ## 3) git checkout new_branch – This command activates a new branch.
 ~~~bash
 git checkout new_branch
 ~~~
 ![image](https://user-images.githubusercontent.com/54863241/196045194-9cc44bd8-4d21-4d07-b6ca-7a1a67c6be24.png)
 
  ## 4) git add .(dot) - This command track all the files in the working directory to the temporary staging area.
 ~~~bash
 git add .
 ~~~
 ![image](https://user-images.githubusercontent.com/54863241/196045289-992a0bf8-8d44-4e88-afe5-ce3791816790.png)
 
   ## 5) git commit -m “commit message” – This command permanently store the contents of the index in the repository with git commit.
 ~~~bash
 git commit -m "commit message"
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196045399-f6ecf557-208b-4ed4-9bca-e63f9912325a.png)
 
   ## 6) git push origin main - This command track all the files in the working directory to the temporary staging area.
 ~~~bash
 git push origin main
 ~~~
 ![image](https://user-images.githubusercontent.com/54863241/196045433-4fb35d64-8323-43d5-82a5-3eae5fabf645.png)
 
   ## 7) git status - This command tells us which files/changes have been staged and which is not staged
 ~~~bash
 git status
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196045773-92ff6da4-641b-47a9-9c55-b4b6e19cac86.png)
 
  
   ## 8) git pull - This command pulls changes from Remote repository to Local repository
 ~~~bash
 git pull
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196046086-5d311cf2-fad0-48bf-adfd-9c2ca6bc9f2e.png)

  
   ## 9) git log - This command lists the history of the commits made in the repository
 ~~~bash
 git log
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196046208-b9e6bca4-e881-437c-b813-9bb66506e0e3.png)

  
   ## 10) git ls-files - This command lists all the files present in the staging area
 ~~~bash
 git ls-files
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196046369-76d87b6b-47fd-4a4c-9b0c-6b6829266c36.png)
 
   ## 11) git stash save "staged sample file name" - The git stash command takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy
 ~~~bash
 git stash save <"staged sample file name">
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196046576-7b173fc6-dc92-4119-9b56-15cf3ca80b75.png)
 
  ## 12) git stash list - This command lists all Stashed Files.
 ~~~bash
 git stash list
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196046689-efca50ad-4759-45b4-b0b6-ff59a606b0fb.png)
 
  ## 13) git stash apply stash@{0} - This command brings back the stashed file to the staging area
 ~~~bash
git stash apply stash@{0}
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196046833-dc1ddf06-2aba-4078-b85d-97679479b906.png)
 
  ## 14) git merge branch name - This command merges the branches
 ~~~bash
 git merge <branch name>
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196047837-b1a01626-1a9d-4f55-aa23-0083c71bf7c2.png)
 
 
  ## 15) git clone - This command clones the contents from remote repository to local repository
 ~~~bash
 git clone <url>
 ~~~
![image](https://user-images.githubusercontent.com/54863241/196047924-7117d7d2-b0be-409b-9465-02921274c25e.png)
 
 
 
 
 
 
 
 
 
 
 
