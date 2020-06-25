# Read: 03 - Revisions and the Cloud

## Version Control

- is a system that allows you to revisit various versions of a file or set of files by recording changes.
- one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes

## Local Version Control (LVCS)

- Local VCS entails one database on your hard disk that stores changes to files

## Centralized Version Control (CVCS)

- This system entails a single server storing all changes and file versions, which can be accessed by various clients.
- The collaboration process
    - Allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.

## Distributed Version Control (DVCS)

- addresses the major vulnerability of the CVS: the server as a single point of failure
- In case of emergency (systems down), a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information

## What is Git?

### Snapshots

- Git is a DVCS that stores data in a file system made up of snapshots. 
- Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.
Local Operations
Git mostly relies on local operations because most necessary information can be found in local resources.

### Tracking Changes

- Every single change applied to any file or directory is tracked by Git

### Loss of Data

- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data.

### States

- Files in Git can reside in three main states: committed, modified and staged.

### Committed

- Data is securely stored in a local database

### Modified

- File has been changed but not committed to the database

### Cloning

- $ git clone https://github/test

### Checking File Status

- $ git status

# ACP

- Add
    - $ git add example.md
- Commit
    - $ git commit -m “Adding some info in file”
- Push
    - $ git push origin master
