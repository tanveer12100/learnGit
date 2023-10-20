# learnGit
In this repository you will learn about Git, how to work using git repositories.


Book : Learn Version Control with GIT by Tobias Gunther

Problem : Files maintenance / version maintenance / change maintainence / working in team problem
Solution : Version control system

Version Control System:

    Version control system is basically used to control versions of your projects, files and other software related stuff.
    
    It is a software utility that tracks and manages changes to a file-system
    
    It is also known as revision control or source control system
    
    It is used to manage changes to documents, computer programs, large websites and other collection of information
    
    VCS is like database, it takes snapshot of project at times
    
    You can view changes / difference between different snapshots
    
    VCS is independent of technology you are working with
    
    In VCS snaphot are taken, but only for those files in a version that are being changed, so less storage is consumed
    
    VCS can be used in team colaboration and individual can also used for single project
    
    VCS heiglights changes in lines of files
    
    VCS are centralized server system to copy files and update changes to that server
    

VCS Types:
  1. VSS
       Microsoft Visual SourceSafe(VSS) is a source control program, oriented towards small software development projects.
  3. SVN
       SVN is the abbreviated form of "Apache Subversion" and is a popular version control system tool. It is a centralized version control system.
  4. GIT

How: In DVCS we commit to save changes locally and when we want to save changes to server than we push and to get it locally we pull repository

Installing and Setting up git environment:
Download git cli or gui from link below
    https://git-scm.com/downloads      // for CLI
    https://git-scm.com/downloads/guis // for GUI

git init // to add folder to git repository, but files are not tracked yet

Command to add files to git repository to be tracked
git add .
git add filename filename
git add *.txt

git commit -m "add files first.txt and second.txt"   // to commit file changes

git Hash: 40 character checksum, a unique identifier 

git reset // to unstage all staged files
git reset --hard // to unstage all staged changes and remove all the updated chenges in files

To ignore files, directories and folders:
create file without name with gitignore extension like .gitignore in master branch of repository, and than write file name and folder names which you want to ignore.

branches are used in git for different context, when a context/scenario is changed a new branch is created for that

git branch               // list all branches
git branch -v            // show list of branches with details
git branch new-brnach     // create new branch
git checkout new-branch   // switch to new branch
git merge branchname      // merge said branch to active branch
git log branchname..master // show commit difference in two branches

