# Git Intro
## Version Control: 
### Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.
## Local Version Control: 
### A Local VCS entails one database on your hard disk that stores changes to files.
## Centralized Version Control: 
### allows for multiple mirrored repositories, programmers working in teams can collaborate in various ways to complete a joint project.
# what is Git?
1. snapshots(Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it)
2. local operation(Git mostly relies on local operations because most necessary information can be found in local resources.)
3. tracking changes(Every single change applied to any file or directory is tracked by Git)
4. loss of data(Git is set up to greatly minimize the possibility of irreversible damage to files)
5. states(committed, modified, and staged.)
# History of Git :
## Git started in 2002 as a Bitkeeper.
## Graphical Clients: 
### Git includes inherent Graphical User Interface (GUI) tools.
## Default Text Editor: 
### Without the configuration of a default text editor, Git will use the system’s default editor–most likely Vim.
## Check Settings: 
### To check settings, use the git config --list command.
## Getting Help: 
### git help command
## Setting up a Git Repository :
- Importing
- Cloning
## Local Repository Structure:
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit
## Saving Changes:
- Tracked 
- Untracked
## Check File Status: 
### git status
## Tracking and Staging a New File :
1. Single File: git add filename
2. All Files: git add *
## Committing a File: 
### After staging one or multiple files, you should commit the changes and record what you did within the commit message.
## Committing All Changes:
### git commit -a
## Pushing Changes: 
### git push origin master