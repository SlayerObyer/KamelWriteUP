
# **Kali linux rooms**
Linux Fundementals#1
Task: A Bit of Background on Linux.
Q:What year was the first release of linux operating system?
A:1991

Task: Running Your First few Commands.
Q:If we wanted to output the text "TryHackMe", what would our command be?
A:Type command "echo TryHackMe" to print in the terminal.

Q:What is the username of who you're logged in as on your deployed Linux machine?
A:Type in your terminal "whoami", then you will find the name of the user you logged in with.

 Task: Interacting With the Filesystem.
Q:On the Linux machine that you deploy, how many folders are there?
A:In order to solve this question we need to use command “ls”, then we will see how many folders in the directory, which is 4 folders.

Q:Which directory contains a file?
A:WE need to use the command “cd folder4”, then command “ls” we will find a .txt file.

Q:What is the contents of this file?
A:We use command "ls" and "cd" to select the directory to find the text file in the following directory "/home/tryhackme/folder4".

Task 6:Searching for Files.
Q:Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag?
A:Using command "grep "THM"" to search in the entities  any thing has "THM".

Task 7:An Introduction to Shell Operators
Q:If we wanted to run a command in the background, what operator would we want to use?
A:Command "&".

Q:If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be?
A:echo password123 > passwords

Q:Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be?
A:echo tryhackme >> passwords.


Linux Fundamentals#2
 Task 3:Introduction to Flags and Switches.
 Q:Whast directional arrow key would we use to anvigate down the manual page?
 WE would use down arrow to review more about tha manual.

 Q:What flag would we use to display the output in a "human-readable"way?
 A:"-h".

 Task 4:Filesystem Interaction Continued.
 Q:How would you create the file named "newnote"?
 A:touch newnote.

 Q:On the deployable machine, what is the file type of "unknow1" in "tryhackme's" home directory?
 A:ASCII text.

 Q:How would we move the file "myfile" to the directory "myfolder"?
 A:mv myfile myfolder.

 Q:What are the contents of this file?
 A:THM{FILESYSTEM}.

 Q:On the deployable machine, who is the owner of "important"?
 A:By typing the command "ls -l" ,It will show the files and thw owners of those files.

 Q:What would the command be to switch to the user "user2"?
 A:Type the command "su user2".
 
 Q:Output the contents of "important", what is the flag?
 A:After we switched to user2 we can use commande "cat Important" to review thr content of the file and we will find "THM{SU_USER2}".

 Task 6:Common Directories.
 Q:What is the directory path that would we expect logs to be stored in?
 A:/var/log.

 Q:What root directory is similar to how RAM on a computer works?
 A:/tmp.

 Q:Name the home directory of the root user?
 A:/root. 


