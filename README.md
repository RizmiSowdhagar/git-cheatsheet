\# Linux + Git Cheat Sheet



This file will hold at least 15 Linux and Git commands.


1) ### pwd

\- Shows the current working directory.

\- Example: `pwd`



2\) ### ls

\- Lists files and directories.

\- Example: `ls`


3) ### cd

\- Change directory.

\- Example: `cd foldername`



4\) ### mkdir

\- Make a new directory.

\- Example: `mkdir test`


5) ### touch

\- Create an empty file or update timestamp.

\- Example: `touch file.txt`


6) ### cat

\- Show file contents.

\- Example: `cat file.txt`



7\) ### mv

\- Move or rename files.

\- Example: `mv old.txt new.txt`


8) ### cp

\- Copy files.

\- Example: `cp file.txt backup.txt`


9) ### rm

\- Remove files.

\- Example: `rm file.txt`


10) ### grep

\- Search text in files.

\- Example: `grep hello file.txt`


11) ### echo

\- Print text to screen.

\- Example: `echo Hello`


12) ### head

\- Show first lines of a file.

\- Example: `head file.txt`


13) ### tail

\- Show last lines of a file.

\- Example: `tail file.txt`


14) ### chmod

\- Change file permissions.

\- Example: `chmod 755 file.sh`


15) ### df

\- Show disk space usage.

\- Example: `df -h`


## Git Basics



1\. \*\*Initialize\*\* a repo  

&nbsp;  `git init`



2\. \*\*Status\*\* of changes  

&nbsp;  `git status`



3\. \*\*Stage\*\* files  

&nbsp;  `git add README.md`  •  `git add .`



4\. \*\*Commit\*\* staged changes  

&nbsp;  `git commit -m "feat: add cheat sheet"`



5\. \*\*View history\*\*  

&nbsp;  `git log --oneline --graph --all`



6\. \*\*Branches\*\*  

&nbsp;  `git branch`  •  `git checkout -b feature-x`



7\. \*\*Merge\*\* into current branch  

&nbsp;  `git merge feature-x`



8\. \*\*Connect remote\*\* (SSH)  

&nbsp;  `git remote add origin git@github.com:<USER>/git-cheatsheet.git`



9\. \*\*Push\*\*  

&nbsp;  `git push -u origin main`



10\. \*\*Pull\*\*  

&nbsp;   `git pull`



---



\### Notes

\- Default branch set to \*\*main\*\*.  

\- Pushed via \*\*SSH\*\* with an \*\*ed25519\*\* key.  

\- Each Linux command was developed on its own branch and merged back to `main`.

