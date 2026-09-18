
1. What did the rejected push error message tell you, and why did it happen
The error message said that updates were rejected because the remote contains work that I did not have.

2. What's the actual difference between how you resolved Task 3 (merge) vs Task 4 (rebase)
- Merge preserves the timeline by creating a new merge commit that merges the two diverging branch histories together. 
- Rebase takes the local commits, then setting them aside, updating the base to match the latest remote commit, and then reapplying the commits.

3. What one habit would have avoided both rejected pushes in this lab
Running `git pull --rebase` before starting the code or attempting to push.

4. Which approach - merge or rebase - would you default to on a shared team branch, and why
Merging is my preferred method as it is safer and preferred for shared team branches because rebasing rewrites the public history. 
