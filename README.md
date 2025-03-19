  

### **Basic Git Commands (Initialization & Setup)**
1. `git init` – Initialize a new Git repository  
2. `git config --global alias.s "status"` – Create a shortcut alias (e.g., `git s` for `git status`)  
3. `git config --list` – View all Git configurations and aliases  
4. `git config --global --unset alias.s` – Unset a Git alias  

---

### **Working with Files & Commits**
5. `git status` – Check the status of the working directory  
6. `git add [file]` / `git add .` – Add specific files or all changes to staging  
7. `git commit -m "message"` – Commit staged changes with a message  

---

### **Branching & Merging**
8. `git branch` – List all branches  
9. `git checkout [branch-name]` – Switch to another branch  
10. `git merge [branch-name]` – Merge a branch into the current branch  

---

### **Remote Repository Management**
11. `git clone [repository-url]` – Clone a remote repository  
12. `git fetch` – Fetch changes from a remote repository  
13. `git pull` – Pull latest changes from a remote repository  
14. `git push` – Push changes to a remote repository  
15. `git push origin [branchname]` – Push a branch to GitHub  

---

### **Branch Deletion**
16. `git branch -d [branch-name]` – Delete a local branch (if merged)  
17. `git branch -D [branch-name]` – Force delete a local branch  
18. `git push origin -d [branch-name]` – Delete a branch from the remote repository  

**Note:** Before deleting a branch, ensure you're not currently checked out to it.  

---

### **Tagging**
19. `git tag [tag-name]` – Create a new tag  
20. `git tag` – List all tags  
21. `git show [tag-name]` – Show details of a tag  
22. `git tag -d [tag-name]` – Delete a tag locally  
23. `git push origin [tag-name]` – Push a tag to GitHub  
24. `git push --tags` – Push all tags to GitHub  
25. `git push origin -d [tag-name]` – Delete a tag from GitHub  
26. `git push origin -d tag1 tag2 tag3` – Delete multiple tags from GitHub  
27. `git checkout [tag-name]` – Switch to a specific tag  

---

### **Viewing and Comparing Changes**
28. `git log` – View commit history  
29. `git diff [file]` – Show changes in a file  
30. `git remote -v` – Show remote repository details  
31. `git blame [file]` – Show who made each change in a file  

---

### **Undoing Changes (Reset & Revert)**
32. `git reset [file]` – Unstage a file  
33. `git revert [commit]` – Create a new commit that undoes a specific commit  
34. `git reset --soft [commit-id]` – Move HEAD to a previous commit, keeping changes staged  
35. `git reset --mixed [commit-id]` – Move HEAD to a previous commit, unstaging but keeping changes in the working directory  
36. `git reset HEAD [file]` – Unstage a file from staging to working area  

---

### **Advanced Git Commands**
37. `git stash` – Stash current changes temporarily
38.  Cherry pick: from particular branch,if we need to the copy data from a specific commit to a another branch.
39. `git cherry-pick [commit-id]` – Apply a specific commit from one branch to another  
40. `git bisect` – Find which commit introduced a bug  
41. `git reflog` – Show a log of all Git references  
42. `git worktree` – Manage multiple working treesClear and Reset GitHub Credentials

cmdkey /delete:git:https://github.com
git remote set-url origin https://github.com/udayapreethi/devops-commands.git
git push



 

---

### **Handling Merge Conflicts**
42. `git merge --abort` – Abort a merge and return to the previous state  

---

