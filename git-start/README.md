# :star2: GIT  

A distrubuted version control system  
  
__Distributed__  
 You don't have to be on the same network

__Version-Control__  
Keeps track of changes  
Coordinates changes among developers  
Keeps track of who made changes and when they were made  
  
It keeps track of code history with snapshots of your file  
Snapshots are made through commits  
You can revist the snapshots  
Files are added to a staging area before commiting  

`git init`- Initializes a local repository  
`git add` - Add file(s) to index/ stagging area  
`git status` - Check the current status of your working tree  
`git commit` - Commit the files that are in the current staging area  
`git push` - Takes the local commited changes and pushes to a remote repository  
`git pull` - Pull the latest version of a remotr repo  
`git clone` - Clone a remote repository to a local machine

__Branches__  
`git branch 'branch_name'` - Creates a new branch  
`git checkout 'branch_name'` - Changes the working branch  
`git branch -D 'branch_name'` - deletes a branch  

__Remote__  
`git remote set-url origin git@github.com:username/repo.git` - Set a remote repo to an existing local project  
