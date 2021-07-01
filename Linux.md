
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

 **Linux Fundamentals Part#3**
 **Task 3:Terminal Text Editors.**
 Q:Edit "task3" located in "tryhackme"'s home directory using Nano. What is the flag?
 A:We need to use command "nano task3", then we will find the flag "THM{TEXT_EDITORS}".

 **Task 4:General/Useful Utilities.**
 Q:What are the contents?
 A:
 1. We need to start firstly python websever by command"python3 -m  http.server".
 2. We need to us this command in another terminal "wget http://MACHINE_IP:8000/.flag.txt" to download the file ".flag.text".  
 3. We need to "cat .flag", we will find the flag in the file"THM{WGET_WEBSERVER}".

 **Task 5:Processes 101.**
 Q:If we were to launch a process where the previous ID was "300", what would the ID of this new process be?
 A:301.

 Q:If we wanted to cleanly kill a process, what signal would we send it?
 A:"SIGTERM".

 Q:Locate the process that is running on the deployed instance (MACHINE_IP). What flag is given?
 A:
 1. Type command "ps aux | less".
 2. Then we will find THM{PROCESSES}.

 Q:What command would we use to stop the service "myservice"?
 A:"systemctl stop my service".

 Q:What command would we use to start the same service on the boot-up of the system?
 A:"systemctl enable myservice".

 Q:What command would we use to bring a previously backgrounded process back to the foreground?
 A:"fg".

 **Task 6:Maintaining Your System: Automation.**
 Q:When will the crontab on the deployed instance (MACHINE_IP) run?
 A:@reboot.

 Q:What is the IP address of the user who visited the site?
 A:10.9.232.111.

 Q:What file did they access?
 A:catsanddogs.jpg.  