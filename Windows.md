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

## Q5:Answer format: username1, username2
A:By using "net user" command you will "Jenny ,Guest ".







