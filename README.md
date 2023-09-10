# LinuxPracticeProject

FILE MANIPULATION

1. Sudo Command: This command helps you work as an administrator and gives the user root privileges

![RobloxScreenShot20230528_205433660](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/07475c25-8746-4773-b2eb-9b714bd374d7)
![Capture](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/2aa9ec7e-d4da-42d4-843a-a0af20f849de)

2. Pwd Command: pwd means present working directory. It helps you navigate to the current working directory. See screenshot below

![pwd](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/05406b65-1449-414c-9ac5-298c1cf343b6)

3. Cd Command: cd means Change Directory. This command helps you switch to a different directory. For example, the command cd Desktop takes you to the desktop folder. Please take a look at the screenshot below.

![cd](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/8b0c53d0-f5c7-4b47-808a-33eac40bbb71)

Using the command cd alone takes you to the previous directory. Please take a look at the screenshot below.

![cd2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/de115e19-dd5b-4a68-a3af-f31d3054676e)

4. ls command: The ls command lists files and directories within a system. Please take a look at the screenshot below.

![ls](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/f4dfe779-e56b-4ca1-a700-57e4c1692487)

The command ls -R displays the files in the subdirectories. Please take a look at the screenshot below.

![ls2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/8b13d8ac-6a4b-4ef2-8a44-86b4b4b9384e)

The command ls -a shows the hidden and visible files, while the command ls -lh shows the file sizes in readable formats. Please take a look at the screenshot below.

![ls3](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/15f00fbf-dce0-43d8-a376-4a8d62b30478)


5. Cat Command: Cat is an acronym for Concatenate. It lists, combines and writes file content to the standard output. e.g. 'cat Firstfile' list the file, and the command 'tac Firstfile' show the content in reverse while the merge file command 'cat secoundfile thirdfile > Firstfile.txt' merges both file into the file named 'Firstfile'  see the screenshot below for each command

![cat command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/20c231e4-8df2-46ae-abc7-6cb8865788eb)
![tac command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/8dad90dc-3706-42fd-9463-3370eba113e0)
![cat merging file command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/215f94f8-6422-401f-8a12-e128a4f03b75)

6. CP Command: This is a copy command in Linux used to copy file or directory and their content. e.g. 
To copy a file to a directory, use the command 'cp Firstfile DevOps/'  see screenshot below

![cp command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/bf000fa8-a727-4e1c-ab64-078914a3350d)

To copy the content of a file into a new or another file in the same directory, use the command ' cp Firstfile Secoundfile' This copies the content of the file named Firstfile into the file named Secoundfile see screenshot below

![cp command 2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/f3a24d88-4f75-4653-ab07-28948541ec76)

To copy an entire directory, use the -R flag and the cp command. Type the source directory followed by the destination directory, e.g. 'cp -R Devops/ Documents/ see the screenshot below

![cp command3](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/d69fa8d7-0706-4077-b3e5-a58af0210921).

7. mv Command: This is a move or rename command in Linux. 
To move a file, use the command 'mv Secoundfile Desktop/' see screenshot below.

![mv command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/ab6145a2-3008-4087-b691-ef13f6d141f3)

To rename a file, use the mv command. eg 'mv /home/joanopel/sqlite /home/joanopel/Firstfile' see screenshot below

![mv  or rename command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/8fa70113-b229-4f06-8841-9a8b3b0e0f39)
![mv  or rename command result](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/802bb5e6-eef5-4f73-90e5-8b9dd9a74ce2)

8. mkdir Command: This command creates one or multiple directories and sets permission for each. See below screenshots

![mkdir](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/c27739b6-425b-43f2-9327-7c1c3a6c1550)
![mkdir2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/a3d3e508-5d36-44f3-8316-4ed9878ad9f9)

9. rmdir Command: This command permanently deletes an empty folder. 
To remove an empty subdirectory and its main folder, use the command 'rmdir -p muzic/2020/songs. See screenshot below

![rmdir2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/a135ba28-6941-4e87-9a54-9942cc2a3119)
![rmdir3](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/d126c463-2a8c-4703-9efb-e4421ae241e1)

10. rm Command: This command is used to delete files within a directory
To delete a file, use the command 'rm Thirdfile' See screenshot below.

![rm command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/1b10e4fe-14f2-4447-8643-5b9f6dfb5342)

11. Touch command: This command creates an empty file and generates and modifies a timestamp in the Linux command.
    To create an HTML file in the Documents director named trial, use the command 'touch Trial.html'. See the screenshot below.

    ![touch command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/95a1eff1-bc57-4f63-bcbb-195449a7780f)
![touch command2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/1d3c3faf-90a5-44a8-8735-c1eff13e11b9)

12. Locate Command: This command helps find a file in a database system.
    An asterisk looks for content with two or more words, and adding the -i arguments will turn off case sensitivity. e.g. 'locate trial'. See screenshot below

    ![locate command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/dd1991fb-81f1-413c-80fd-01f2cf10c680)

13. Find Command: The find command searches for a file in a specific directory. e.g. 'find Documents -name trial.html' see screenshot below

   ![find command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/55c8a801-630d-40b0-89f9-e89be2c40506)

14. grep Command: grep stands for Global Regular Expression Print. The command searches for words by scanning through all the text in a particular file. This is especially 
    useful in a large file log. e.g. To search for the word 'command' in the file named 'Firstfile', use the command 'grep command Firstfile' see screenshot below

    ![grep command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/154affd3-7cab-404f-9cac-849db4fda080)

15. df Command: This command displays the current directory or file disk space in KB or Percentage
    Use the command 'df -h' to see the current directory disk space. See the screenshot below.

![df command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/ac42c8b7-2033-4b5a-bf5e-1a21bca69ea7)

    To display the disk space a particular file uses, use the command 'df -h Firstfile' See screenshot.

 ![df command2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/c88ce743-f905-48f9-af5c-4b47ce83ed76)


16. du Command: This command checks how much space a file or directory uses up. This command helps to tell which part of the system uses the storage excessively
    e.g 'du Documents/DevOps' See screenshot below

   ![du command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/6c909626-8a45-4544-a01b-37d9198c7314)
   ![du command2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/445a4105-dd89-41a1-81d5-84d52ed22038)

17. Head command: This command displays the first lines of a file, and it can be customised to a specific number of lines.
    To get the first six lines of a file, use the command 'head -n 6 Firstfile' see screenshot below
    
    ![head command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/0e459c84-ae04-40a9-ac02-ff637dcaa98d)

18. Tail Command: This command displays the end of a file. It is especially useful to check for new data in a file or to check for error message
    e.g. 'tail -n 4 Firstfile' see screenshot below
    
![tail command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/2d5179c1-c195-4905-86f5-dde524af8d61)

19. diff command: This is an acronym for difference. This command compares two files line by line and displays the outputs of the parts that do not match.
    To see the difference between a file named Firstfile and Firstfile.txt, I used the command ' diff Firstfile Fisrtfile.txt'. See the result in the screenshot below.

   ![diff command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/aaa753cd-70ca-49ca-87f3-5e223a869251)

20. tar Command: This command combines multiple files into a folder or file. It is similar to a ZIP file that compresses files together inside a folder
    To create a new Tar file, use the command ' tar -cvf Newachive.tar home/joanopel/' See screenshot below.
    
 ![tar command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/ef355df4-904a-48a5-beba-57285fb371aa)

   FILE PERMISSIONS AND OWNERSHIP

21. chmod Command: This command helps to modify a file or directory read, write and execute permission.
    To change the read, write and execute permission for the file named Firstfile and Firstfile.txt I used the following command 'chmod 777 Firstfile Firstfile.txt' see screenshot below

   ![chmod command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/99b866c1-845d-4e9a-af08-79425397685f)


22. chown Command: This command helps to change the ownership of a file or directory.
    To change the ownership of a file named Firstfile.txt to a new guest user. I used the following command: 'sudo chown guest Firstfile.txt'. See the screenshot below.

    ![chown command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/a8a90169-3c32-446d-9a23-e7b616782fae)

23. jobs command: This command starts a process in the shell to display all the running processes and their status.
    The command is 'ps' to display the status of jobs in the shell. Other options are -f, -n and -1 display various information. See the screenshot below.

    ![jobs command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/5ee12da6-6f06-40ba-8b53-86a600b99850)
    ![jobs -n -1 command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/079a234b-cf5d-4d47-ae63-7a1ada7d6143)

24. kill command: This command terminates a program.
    To do this, I used the command 'ps ux' to know the pid and the command 'kill 3821' to terminate the program.

    ![ps ux command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/ff817c3b-2d92-4b73-aba5-73bd32d41d40)
    ![kill command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/4973b5ff-ff53-4a7f-9681-23323bb1e59f)

25. ping command: This command is used to check if a network or server is reachable and troubleshoot connectivity issues
    To do this, use the command ' ping google.com'

    ![ping](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/0989aefe-b8cd-43cc-8f2d-94a98a71d4dd)

26. wget command: This command helps to download files from the internet
    To do this, I used the command 'wget https://wordpress.org/latest.zip' See the screenshot below

    ![wget command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/55eaed98-e051-4900-a381-1d91642a9903)


27. uname command: This is an acronym for Unix name. This command gives detailed information about the Linux operating system, the hardware and the kernel
    To display the information, run the command 'uname -a' See the screenshot below.

    ![uname command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/ed36432e-5fae-43aa-8b95-b40546692c15)

28. top Command: This command displays current processes and gives a real-time view of the system and can be used to identify and terminate a process that uses too many resources
    To do this, I used the command 'top' on the CLI. See screenshot.

    ![top command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/b425b893-603a-42f5-a208-67c8d7e4555f)

29. history command: This command lists previously used commands and allows them to be reused without re-entering them
    see screenshot below

      ![history command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/05080fb6-08f4-47d5-a27e-f29d8c478d1c)
      ![history command2](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/e7e6a89c-1eae-4b97-b89a-a4b7aaafbebd)

30. man command: This command provides information or a manual regarding a command in Linux, such as name description and options to use the command
    see screenshot below

    ![man command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/4b4afe60-b222-4e4f-ae00-3f65d8d6162b)

31. echo command: This command displays a line of text or string in a file to the standard output
    see screenshot below

    ![echo command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/45e78fcb-c4dd-4c14-8969-5300f01c16e3)

32. zip and unzip Comand: This command is used to compress files into zip files and is useful for reducing disk usage
    To do this, run the command 'zip. Newachive.zip Frstfile' and to Unzip run the command 'unzip achive.zip.' see screenshot below.

    ![zip command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/6cd51194-841f-4f2d-982b-5f80304505d5)
    ![unzip command](https://github.com/Nsidibeopel/LinuxPracticeProject/assets/143354400/e83a2cbd-ac89-4b86-aba2-6ea6b6f760eb)
    
33. 
    
    
