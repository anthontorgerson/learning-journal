# Version Control

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. With this, you can revert a file
or project to a previous version, track modifications and modifying individuals and compare changes. By using a Version Control System (VCS), mistakes
with files can easily be caught & fixed.

- **Local Version Control** entails one database on your hard disk that stores changes to files.

- **Centralized Version Control (CVCS)** is a single server storing all changes and file versions, which can be accessed by various clients. This allows
programmers to have more knowledge of team members’ activities with certain files, and gives administrators better control over divvying up revision privileges.

- **Distributed Version Control (DVCS)** addresses the vulnerability of the CVS: the server as a single point of failure. If a CVS server goes down, team members cannot work
on files or save changes or updates. Also without backups, all the work will be lost (other than what's saved on local machines).

 
# What is Git?

Git is a DVCS that stores data in a file system in the form of snapshots. Every time you save or make a change to your project (this is called a __*commit*__), Git creates a
snapshot of the file with a reference to it (_a line entered by the programmer explaining shortly what change was made_). It relies mostly on local operations because most
necessary information is found on local resources. This makes it easier because it doesn't have to communicate with the servers for the programmer to work on a project;
they can work on it offline or without a VPN. Git is setup up to minimize the possibility of losing data because every change applied to every file or directory is tracked
by Git and it will always detect file corruption or loss of files.

### **States**

Files in Git can reside in the 3 following states:

* _*Committed*_ : Data is securely stored in a local database.
* _*Modified*_ : File has been changed, but not committed to the database.
* _*Staged*_ : Flagged a file's changed version to be committed in the next snapshot.


For instructions on downloading Git & adding customizations, click [HERE](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#2_1) and go to _Getting Started_.


## Setting up a Git Repository

### Importing

To import an existing project, enter the following lines of code in your Terminal or Command Line:

* $ cd test (cd = change directory)
* $ git init
* $ git add *.c
* $ git add LICENSE
* $ git commit -m “any message here / programmer notes”

Now your files are tracked & there's an initial commit.


### Cloning

To create a copy of an existing repository, enter the following command:

* $ git clone https://github.com/test

To create a copy of an existing repository with another name, enter the following command:

* $ git clone https://github.com/test mydirectory


For more info on saving changes, checking file status, tracking & staging a new file, committing a file, pushing changes, stashing changes, cloned repositories &
seeing your remotes, click [HERE](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#2_1) and continue down from _Workflow_.


- [Return To Home - 102](/README.md)


