I used the following git commands for this task and was able to understand and learn these git commands after doing this task.

1) git verify : it is used to verify the integrity of git objects and ensure our repository hasn't been corrupted.

2) git commit : it saves our changes in the staging area in the local repository.

3) git reset
Moves the HEAD pointer to a specified commit and optionally changes the staging area and working directory.

4) .gitignore
A configuration file that specifies which files and
directories Git should ignore and not track.

5) git merge
Combines changes from one branch into another.

6) git stash
Temporarily saves uncommitted changes, allowing the user to switch branches
or perform other operations without committing.

7) git stash pop
Applies the most recent stashed changes back to the working directory and
removes them from the stash list.

8) git rebase
Reapplies commits from the current branch on top of another base commit,
creating a cleaner and linear project history.

9) git rebase --continue
Used after conflicts occur during a rebase to continue the process once the
conflicts have been resolved.

10) git rm
Removes files from both the working directory and the staging area.

11)  git mv
Renames or moves a file while automatically staging the change.

12)  git commit --amend
Modifies the most recent commit by changing its message or adding new changes.

13)  git commit --amend --date
Revises the most recent commit and changes its timestamp.

14)  git rebase -i HEAD~2
Performs an interactive rebase on the last two commits, allowing edits, 
deletions, squashes, or rewording of commit messages.

15)  git reflog
Displays a log of all changes made to the HEAD reference, 
including those that have been reset or detached.

16) git reset 
Resets the repository’s state to a specific commit, altering the HEAD,
staging area, and working directory based on the chosen option.

17)  git rebase --interactive
Provides an interactive way to edit, reorder, squash, or remove multiple
commits. It is equivalent to git rebase -i.

18) git update-index --chmod=+x <file> 
It adds the executable bit to the specified file in the git index.
when we commit this change the executable permission will be recorded in the
repository.

19) git add -p
Allows us to stage part of the changes we have made to a file.

20) git cherry-pick
Applies a specific commit from one branch onto another branch.
It allows selective inclusion of commits without merging the entire branch.

21) git cherry-pick --continue
Continues the cherry-pick process after conflicts have been resolved. It is used when a cherry-pick operation is interrupted due to merge conflicts.

22) git rebase --onto
Reapplies a range of commits onto a new base commit or branch. This command provides fine-grained control over the starting and target points of a rebase operation.

23) git log -S
Searches the commit history for commits that add or remove a specific string or code fragment. It is useful for identifying when and where a particular line of code was introduced or deleted.

24) git bisect start
Begins the binary search process used to identify the commit that introduced a bug. It initializes the bisect operation.

25) git bisect bad HEAD
Marks the current commit as a “bad” commit, indicating that the bug or issue is present in this version.

26) git bisect good 1.0
Marks a known commit as “good,” signifying that the bug was not present in that version. This establishes a comparison point for the bisect search.

27) git bisect run sh -c
Automates the bisect process by executing a shell command or script to test each commit. The result of the command determines whether each commit is classified as good or bad during the search process.
