# GO_GitPractice
First day of Internship at GO - Practice using git and github

##
**1.	How to create repository**
**2.	How to push code to github. Use git add, git commit, git push**
-	Git add <some files> to add files to stage area. Git add . to add all the modified files to the stage.
-	Git commit to push files in stage to local repository.
-	Git push to push files in local repository to remote repository.

 
**3.	How to create a new branch with git checkout**
-	To create new branch: git checkout -b branch_name
With -b flag to ask git to create a new branch if this branch has not existed

**4.	How to use git stash, git log, git rebase**
-	Git stash to temporarily save the uncommitted file (staged and unstaged) to stash and remove them from the workspace. Use git stash apply to get back those files from stage.
-	Git log to show the commit history of the current branch. Git log –oneline (show the list of commits in a short pattern), git log –graph ( show the list of commits in graph pattern)
-	Git rebase move all the unique commits of the feature branch into the top commit of the current branch. Make the history clearly.
  
**5.	Learn about how git works**
**6.	Understanding how to name branches in git flow**
-	Branch name:  
o	Main

o	Release

o	Develop

o	Feature

o	HotFix

-	Workflow:
o	A develop branch is created from main.

o	A release branch is created from develop.

o	Feature branch is created from develop.

o	Feature branch will be merged to develop when it is completed.

o	Release branch will be merged to develop and main when it is completed

o	HotFix branch is created from main when an issue is detected

o	HotFix branch will be merged to main and release when it is completed
