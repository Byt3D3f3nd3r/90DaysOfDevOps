# Day 10 Task: Deep Dive in Git & GitHub for DevOps Engineers.

Day 10 article : [Medium](https://medium.com/@rejani2906/day-10-advance-git-github-for-devops-engineers-878492b583c3)


## Task 1:
 Add a text file called version01.txt inside the Devops/Git/ with “This is first feature of our application” written inside. This should be in a branch coming from `master`,  [hint try `git checkout -b dev`], swithch to `dev` branch ( Make sure your commit message will reflect as "Added new feature").
 [Hint use your knowledge of creating branches and Git commit command]

 1) version01.txt should reflect at local repo first followed by Remote repo for review.
 [Hint use your knowledge of Git push and git pull commands here] 

![add-commit](/2023/day10/Screenshots/1-1-add-commit.png)

![push](/2023/day10/Screenshots/1-1-push.png)

 2) Add new commit in `dev` branch after adding below mentioned content in Devops/Git/version01.txt:
 While writing the file make sure you write these lines
 
 - 1st line>>  This is the bug fix in development branch
 - Commit this with message “ Added feature2 in development branch”
 
 - 2nd line>> This is gadbad code
 - Commit this with message “ Added feature3 in development branch
 
 - 3rd line>> This feature will gadbad everything from now.
 - Commit with message “ Added feature4 in development branch

![commit](/2023/day10/Screenshots/1-2-git-commit.png)

![logs](/2023/day10/Screenshots/1-2-git-log.png)

 3)Restore the file to a previous version where the content should be “This is the bug fix in development branch”
 [Hint use git revert or reset according to your knowledge]

![reset](/2023/day10/Screenshots/1-3-reset.png)

## Task 2:

 - Demonstrate the concept of branches with 2 or more branches with screenshot.

 ![new-branch](/2023/day10/Screenshots/2-1-new-branch.png)

 - add some changes to `dev` branch and merge that branch in `master`

 ![merge](/2023/day10/Screenshots/2-2-merge.png)

 - as a practice try git rebase too, see what difference you get.

 ![rebase](/2023/day10/Screenshots/2-3-rebase.png)