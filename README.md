# GIT-LEARN
  SOME OF THE IMPORTANT COMMANDS AND ITS PURPOSES
=====================================================================================

<h1>1.git init</h1>
  Used when we wanted to initialize a new local Git repository
<h1>2.git clone "repo-url" </h1>
  Used when we wanted to create a copy of a remote repository to your local machine<br>
  When we want to work on a existing project from Github
<h1>3.git status</h1>
  Will show changes (staged, unstaged, untracked)<br>
  When we want to check the current state of your repo
<h1>4.git add .</h1>
    used to add all files in current directory
<h2>git add filename</h2>
    adds only specific file
<h1>5.git commit -m "message"</h1>
  To save the changes that u have made into the local repository
<h1>6.git pull origin main</h1>
  To Fetch + merge changes from remote to local<br>
  When we want the latest version of code from the remote repo
<h1>7.git push origin main</h1>
  To upload local commits to a remote repository<br>
  When we want to share our changes with others
<h1>8.git log</h1>
   To view commit history and also to see the previous commits and messages
<h1>9.git branch </h1>used to List branches
  <h2>git branch new-feature</h2>used to Create new branch<br>
  <h2>git branch -d branch1</h2>used to Delete branch
<h1>10.git checkout branch1 </h1>
  used to switch between branches
  <h2>git checkout -b new-branch</h2>used to perform both Create + switch in a single command
<h1>11.git merge feature-branch</h1>
  To Merge changes from one branch into another.<br>
  Use when: You finish a feature and want to combine it into main/master.
<h1>12.git stash</h1>To temporarily save uncommitted files<br>
  <h2>git stash apply</h2>A copy will be in the virtual even after committing<br>
  <h2>git stash pop</h2>Deleted the copy thast saved temporarily

