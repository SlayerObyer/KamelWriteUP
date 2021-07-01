# [Windows](https://tryhackme.com/room/investigatingwindows)
## <span style="color: red;"> Windows Room </span>
>===============

## Q1:Whats the version and year of the windows machine?
A:
1. Useing Command "systeminfo" can get the information to the system.
2. The answer is "Windows Server 2016.

## Q2:Which user logged in last?
A:
1. Using command "whoami" in cmd would give you result "Administrator".

## Q3:When did John log onto the system last?
A:
1. Using command "net user John".
2. Find the last time he signed.

## Q4:What IP does the system connect to when it first starts?
A:
1. Open Registry Editor.
2. GO to the tab "HKEY_LOCAL_MACHINE" ,"MICROSOFT" ,"WINDOWS" ,"CURRENT VERSION" ,"RUN" .
3. You willl find the script that has the IP Adress"10.34.2.3".

## Q5:What two accounts had administrative privileges (other than the Administrator user)?
A:By using "net user" command you will "Jenny ,Guest ".

## Q6:Whats the name of the scheduled task that is malicous?
A:
1. Open Task Scheduler.
2. Check every tab .
3. Open "clean file system".
4. Check the Trigger and The Action tabs.


## Q6:What file was the task trying to run daily?
A:
1. Open Task Scheduler.
2. Check every tab .
3. Open "nc.ps1".
4. Check the Trigger and The Action tabs.

## Q7:What port did this file listen locally for?
A:
1. As we did before in the previous question in"Task scheduler".
2. Check clean file system.
3. Check Action tab.
4. You will find the port 1348.

## Q8:At what date did the compromise take place?
A:
1. Open Task Scheduler.
2. Choose "Game Over".
3. Check Triggers tab 
4. Answer 3/2/2019.

## Q9:At what time did Windows first assign special privileges to a new logon?
A:
1. Open Viewer.
2. Use filer by date.
3. 2/13/2019

## Q10:What tool was used to get Windows passwords?

A:mimikatz.

## Q11:What was the attackers external control and command servers IP??
A:
1. C:\\Windows\Systeem32\drivers\etc
2. Check the text file and open it.
3. Chcek the ip addresses you will find it not reasnoable.
4. The answer "76.32.97.132".

## Q12:What was the extension name of the shell uploaded via the servers website?
A:
1. Go to "C" then inetpub.
2. Then wwwroot
3. Answer .jsp

## Q13:What was the last port the attacker opened?
A:
1. Go to Windows FireWall.
2. Check the Inound Rules.
3. You will find outside connection for the development Properties.
4. Check the port
5. 1337.

## Q14:Check for DNS poisoning, what site was targeted?
A: google.com



