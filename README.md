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
   
    


    
