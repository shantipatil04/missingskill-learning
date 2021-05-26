<br>
<br>

<div style="text-align: center"> 

# **Linux**
</div>
<br>

<u>

## **History** :

</u>

<div style="text-align: justify"> 
<font size="4">
In the 1970’s Bell Lab had the research on a computer was getting created before that the computer was only used by NASA or DARPA. They had spent one year creating a system called UNIX. After some time lots of company uses the UNIX System. one of the university Started using this System called Berkeley. But they had to pay a lot of money for one UNIX System. After that Berkeley and an ex-employee of Unix came together and had some research and started a new System Called is as a BSD(Berkeley Software Distribution). This was the first cheaper software as the other company would able to use it. In the 1980’s there is a guy called Riechel Stallment he wanted to do some research on a computer but because of the licensing nature, he was not able to pay for the system he wanted. After that, he had some research and create his own free software of free operating system. So Unix was the First Operating System. In 1985’s he started a new organization called FSF (Free Software Foundation). After That, he Started Creating his own Operating System called GNU it had the kernel called HURD but there is less adaption for this. In the 1990s there is Guy called Linus Torvalds and he wanted to use these BSD And GNU systems but he didn’t like Any one of those. So, he spends some time and created his own kernel(is nothing but the software code which interacts with the hardware) it’s low-level software and he made it available completely for free from 1991. In 1991’s Riechel Stallment and Linus Torvalds came together and create GNU Linux which is free of cost. So, Linux is not an OS it’s a kernel and GNU Linux is A OS. Riechel Stallment and Linus Torvalds were God's Father of Free software. Google is also built on GNU Linux. After That, they create the Free version of the terminal and shell called Bash. The most popular operating system for Linux is Red Hat.

 </div>

<br>
<u>

## **Commands:**

</u>
<br>

<div style="text-align: justify">
<font size="4">

**1. ls(List) Command:** List out All the files and folders.

**2. cd(Change Directory) command:** This command is used to change from one folder to another.

**3. cp (copy) command:** This command copy the file from one location to another location.

**4. mv(move) command:** This command is used to move the file.

**5. rm(remove) Command:** This command is used to remove the file. Once you remove the file u cannot retrieve it.

**6. pwd(Print Working Directory):** This command is used to print the path of the current working directory.

**7. who Command:** This command is used to display how many users log in to the system.

**8. whoami Command:** This command displays the username of the current user.

**9. history Command:** This command is used to display the previously executed command.

**10. exit Command:** It is used to exit the Terminal.

**11. cat Command:** This command is used to open the file.

**12. less Command:** This command is similar to the cat command but it only prints the output one page at a time.

**13. echo Command:** This command is used to display the line of text/string that passed as an argument, printing the system path.

**14. top command:** This command is used to give all system-level information.

**15. ps command:** This command list down all the application running in the system.

**16. touch command:** This command is used to create a new file.

**17. ping command:** This command is used to check the connectivity with the internet.

**18. ifconfig command:** This command is used to display the IP address of the system.

**19. ssh (Secure Shell) command:** This command is used to provide a secure connection between two hosts.

**20. mkdire command:** This command is used to create the new directory.

**21. rmdir command:** This command is used to remove the directory.

**22. rename command:** This command is used to rename the file.

**23. which Command:** This command is used to give the location of the software install.

**24. wget command:** wget Command is nothing but the command line browser used for downloading files from the internet.

**25. clear command:** This command is used to clear the terminal screen. Also, use the ctrl+L to clear the screen.

**26. tail command:** This command is used for continuous reading same as a cat but cat print the data and complete the process and exit the terminal and tail command is continuously reading a file and displaying the file.
           Eg. tail -100f filename: display the last 100 lines of the file.

**27. man (manual)command:** This command gives the detail of particular command.

- e.g, man ls: It displays all the flags in detail. 
           

</div>

### **ls (List) Command Flags:**
<div style="text-align: justify">

- ls –l: This command display list of all the files and folder.

- ls –l –h: h stands for Human Readable. Display the output in a human readable format.

- ls –t: It is used to display the files in ascending order i.e., the latest one coming on top and old files is on the bottom.

- ls –r: It is used to display the files in descending order i.e., the old file is on top and the old one on top.

- ls –F: This for to check the directory or folder. It adds the ‘ / ‘ at the end of the directory.

- -a: This flag is used to display the hidden file.

[Command: ls –l –h –t –r –F or ls –lhtrF display the same result]

- **ls --help command:** This command is used to display all flags for the ls command.



</div>

<div style="text-align: justify">



### **cat Command:**

 It is either used for write into the file or can be used for reading from the file.

* cat > filename: Used for write into the file. For updating files, we use the ‘ >>‘ double angle bracket.

* cat filename: Used for reading the file.

### **cd command:** 

 It will go to the user's home folder. Also, use the ‘ cd ~ ’ command for it.

- cd – command: This command is used for go to the previous folder.

- cd .. : This is used for go to the one step back.

- cd ../another folder name: It will go to another folder.



**mkdir 02/skill 03/skills –p:** make the two files inside the directory 02 and 03.

### **rm command:**

* rm –rf filename: This command deletes all the files and folder in the directory.
-rf flag:
R stands for recursive.
F stands for force.

* rm *: this command only deletes all the files inside the folder, not a folder.

* rm –rf *: This command deletes all the files and folders 

* rm skill/linux: Delete the Linux file inside the skill folder. And for deleting the directory we use rm –rf skills/directory name.

**/bin command:** store all the commands.

<br>

<u>

## **File System of Linux:**

</u>

In Linux everything is considered as a file.Example, program, memory, folder, etc., considered as a file.

Root file system starts with '/'.

**1. /boot:** In this system kernel is stored. Kernal configuration and application are stored here.

**2. /bin:** All the user-level Binary Application are stored or and all the commands are stored here.

**3. /sbin:** /sbin is the system binary. It is related to the Linux kernel and used by system admin not used by a normal user.

**4. /home:** All the user data and configuration are stored here.

**5. /var:** All the system level variables are stored here. eg, log files.

**6. /usr:** In this, the user-related files are stored. It is called a system resource.

**7. /root:** The main system user is created inside the root folder.

**8. /temp:** This is a temporary folder. This is used when the system wants to store something temporarily.

**9. /etc:** In this folder system configuration or software configuration are stored.

**10. /lib:** In this folder, system-level libraries are stored.

**11. /mnt:** This folder is basically designed for CD ROM.

**12. /dev:** In this folder, the  Hardware such as RAM, USB, keyboard, Mouse all are attached here. All the External devices are attached here.

**13. /opt:** This gives the information about the software. User-related software is stored here.

**14. /proc:** This is used to store all system-related information.

**15. /CPU info:** This command displays about how many CPUs the system has.

**16. /chown:** It stands for the change ownership. It is used for changing the ownership of a given file.

</font>

</div>


