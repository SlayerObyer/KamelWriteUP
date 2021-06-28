
# **Kali linux rooms**
Linux Fundementals
Task: A Bit of Background on Linux.
Q:What year was the first release of linux operating system?
1991

Task: Running Your First few Commands.
Q:If we wanted to output the text "TryHackMe", what would our command be?
Type command "echo TryHackMe" to print in the terminal.

Q:What is the username of who you're logged in as on your deployed Linux machine?
Type in your terminal "whoami", then you will find the name of the user you logged in with.

 Task: Interacting With the Filesystem.
Q:On the Linux machine that you deploy, how many folders are there?
In order to solve this question we need to use command “ls”, then we will see how many folders in the directory, which is 4 folders.

Q:Which directory contains a file?
WE need to use the command “cd folder4”, then command “ls” we will find a .txt file.

Q:What is the contents of this file?
We use command "ls" and "cd" to select the directory to find the text file in the following directory "/home/tryhackme/folder4".

Task 6:Searching for Files.
Q:Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag?
Using command "grep "THM"" to search in the entities  any thing has "THM".

Task 7:An Introduction to Shell Operators
Q:If we wanted to run a command in the background, what operator would we want to use?
Command "&".

Q:If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be?
echo password123 > passwords

Q:Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be
echo tryhackme >> passwords.
