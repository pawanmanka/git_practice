Git Practice

- Delete local Branch :
    git branch --delete branch_name       OR  git branch -d branch_name  

if use -D = force delete  

- Delete Remote Branch :
    git push origin --delete branch_name  OR  git push origin -d 
    
- Rename only local branch not remote branch
    git branch -m development-branch  
    // Rename on local and then push on remote than need to delete old branch from repo

- For Rename Remote branches 
  ** (IMP)** first checkout in that branch then delete that branch from remote  
	1. git push origin -d development
	2. rename local branch development => staging : git branch -m staging
	3. After Rename push on Remote  : git push origin -u staging


