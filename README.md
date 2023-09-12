# This is Linux Command Project

---
*Linux is a Unix-Like operating system*

## Commands
*A linux command is a program or utility that runs on the CLI-a console that interacts with the susyem via text and processes*

1. ### **sudo command**


>This command is often use to access the root from the regular user account.
  >+ Here is the general syntax (e.g apt upgrade)

*the command to run is*

`sudo apt upgrade`

![Alt text](<image/Screenshot 2023-09-05 at 4.18.59 AM.png>)

2. ### **pwd command**

>It is used to find the present working directory
   +The syntax is pwd [option]

*the command to run is*

`pwd`

![Alt text](<image/Screenshot 2023-09-05 at 5.39.45 AM.png>)
![Alt text](<image/pwd -l.png>)

3. ### **cd command**

>It is used to navigate through Linux files and directories. You can invoke it by specifying a folder to move into
+The syntax is [cd CommandsLinux]

*Now,we can run the below command*

`cd /home/ubuntu/CommandsLinux`

![Alt text](image/cd.png)

4. ### **ls commands:**

>This is used to list the files and directories in a system, using the below command

`ls`

![Alt text](image/ls.png)

>If you add a folder name or path, it will print that folder contents.

For example:

`ls -R`

![Alt text](<image/ls -R.png>)

5. ### **cat command:**

>In its simplest usage, `cat` prints a file's content to the standard output:

`cat`

>For example ,lets run:

`cat sqlite_commands.sh`

![Alt text](image/cat.png)

6. ### **cp command**

>This is used to copy a file or folder.
>
>Let us run an examples of `cp`

`cp sqlite_commands.sh /home/ubuntu/unixcommands`

![Alt text](<image/Screenshot 2023-09-05 at 6.29.14 AM.png>)

7. ### **mv command**

>This is basically used for move and rename files and directories
>Simply type `mv` followed by filename and thhe destination directory

>An example is:

`mv `

`mv sqlite_commands1.sh /home/ubuntu/commandlinux`

![Alt text](mv.png)

8. ### **mkdir**

>This is used to create one or multiple directories.
>Let's create a sample folder using `mkdir`
>
`mkdir Quran`

![Alt text](Mkdir.png)

![Alt text](image/Mkdir.png)

9. ### **rmdir**

>This is used to permanently delete an emply directory
>Now, let's run a sample command for `rmdir`
>

`rmdir Quran/chapter`

![Alt text](<Screenshot 2023-09-11 at 4.26.31 PM.png>)

10. ### **rm command**

>The `rm` is used to delete a file within a directory
>A general example is `rm filename`
>Now lets try to run a command

`rm fish`

![Alt text](rm.png)


11. ### **touch**

>It allows user to create an empty file or generate and modify a time stamp in the linux command line
>For example `touch file_name`

>The command can be run as

`touch cat`

![Alt text](touch.png)

12. ### **locate command**

>It finds a file name in the database sysytem

`locate file1`

13. ### **find command**

>It is used to search for file in a specific directory.

`find`

>An example is:

`find /home -name readme.txt`

![Alt text](image/find.png)

14. ### **grep command**

>`grep` let's us find a word by searching through all the text in a specific folder
>
>An example goes thus:

`grep value sqlight_commands.sh`

![Alt text](image/grep.png)


15. ### **df command**

>It is basically used to report the system disk's storage
>
>It can simply be run as 

`df -h`

![Alt text](image/df-.png)

16. ### **du command**

>It is used to check how much space a file or directory is taking
>
>An example is:
>
>`du /home/ubuntu/commandlinux`








