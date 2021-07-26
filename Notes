#Git Notes
*Version Control-
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.
*Local VCS-
entails one database on your hard disk that stores changes to files.
*Centralized Version Control System (CVCS)-
This system entails a single server storing all changes and file versions, which can be accessed by various clients.
*Distributed Version Control systems (DVCS)-
addresses the major vulnerability of the CVS: the server as a single point of failure.
*Snapshots-
Git is a DVCS that stores data in a file system made up of snapshots. 
*Local Operations-
Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.
*Tracking Changes-
Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
*Loss of Data-
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
*States-
Files in Git can reside in three main states: committed, modified and staged.
*Committed-
Data is securely stored in a local database
*Modified-
File has been changed but not committed to the database
*Staged-
Flagged a file’s changed version to be committed in the next snapshot
*An inherent Git tool called git config-
allows the setting of configuration variables that control aspects of Git’s operation and look.
After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.
*Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:
$ git config --global core.editor emacs
*To determine the state of files, utilize the git status command:
$ git status
*Single File
Track one file only by using the following format:
git add filename
*All Files
Track all files in a repository by using the following command:
$ git add *
