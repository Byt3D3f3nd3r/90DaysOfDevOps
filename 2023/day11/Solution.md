# Day 11 Task: Advance Git & GitHub for DevOps Engineers - Part-2

Day 11 article : [Medium](https://medium.com/@rejani2906/day-11-advance-git-github-for-devops-engineers-part-2-eb7c810301e7)

# Task-01

- Create a new branch and make some changes to it.

![change](/2023/day11/Screenshots/1-1-change.png)

- Use git stash to save the changes without committing them.

![stash](/2023/day11/Screenshots/1-2-stash.png)

- Switch to a different branch, make some changes and commit them.

![commit](/2023/day11/Screenshots/1-3-commit.png)

- Use git stash pop to bring the changes back and apply them on top of the new commits.

![stash-pop](/2023/day11/Screenshots/1-4-stash-pop.png)

- Log file

![log-file](/2023/day11/Screenshots/1-git-log.png)

# Task-02

- In version01.txt of development branch add below lines after “This is the bug fix in development branch” that you added in Day10 and reverted to this commit.

- Line2>> After bug fixing, this is the new feature with minor alteration”

  Commit this with message “ Added feature2.1 in development branch”

- Line3>> This is the advancement of previous feature

  Commit this with message “ Added feature2.2 in development branch”

- Line4>> Feature 2 is completed and ready for release

  Commit this with message “ Feature2 completed”

  ![commit](/2023/day11/Screenshots/2-1-commits.png)

  ![log](/2023/day11/Screenshots/2-2-log.png)

- All these commits messages should be reflected in Production branch too which will come out from Master branch (Hint: try rebase).

  ![rebase](/2023/day11/Screenshots/2-3-rebase.png)

# Task-03

- In Production branch Cherry pick Commit “Added feature2.2 in development branch” and added below lines in it:
- Line to be added after Line3>> This is the advancement of previous feature
- Line4>>Added few more changes to make it more optimized.
- Commit: Optimized the feature

  ![commit](/2023/day11/Screenshots/3-1-commit.png)

  ![cherry](/2023/day11/Screenshots/3-2-cherry.png)
