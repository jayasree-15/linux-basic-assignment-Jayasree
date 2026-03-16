# Linux Basics Assignment

Name: Jayasree
Repository: linux-basic-assignment-Jayasree

## SECTION 1 – Purpose and Example Usage of Commands

### 1. pwd

Purpose:
The pwd command is used to display the current working directory in the Linux system.

Example:
pwd

### 2. ls

Purpose:
The ls command is used to list the files and directories in the current directory.

Example:
ls


### 3. cd

Purpose:
The cd command is used to change the current directory.

Example:
cd Documents

### 4. mkdir

Purpose:
The mkdir command is used to create a new directory in Linux.

Example:
mkdir project

### 5. rm -rf

Purpose:
The rm -rf command is used to remove files and directories forcefully, including all contents inside the directory.

Example:
rm -rf project


### 6. ps -ef

Purpose:
The ps -ef command is used to display all the running processes in the system with detailed information.

Example:
ps -ef


### 7. top

Purpose:
The top command is used to display the running processes in real time and shows CPU and memory usage.

Example:
top


### 8. df -h

Purpose:
The df -h command is used to check the disk space usage of the system in a human-readable format.

Example:
df -h


### 9. history

Purpose:
The history command is used to display the list of previously executed commands in the terminal.

Example:
history


### 10. uptime

Purpose:
The uptime command is used to show how long the system has been running since the last restart.

Example:
uptime


## SECTION 2 – Linux Commands for Tasks

### 1. Create a directory called project-files

Command:
mkdir project-files

### 2. Navigate into the project-files directory

Command:
cd project-files

### 3. Create a file called notes.txt using vi

Command:
vi notes.txt

### 4. Display the contents of notes.txt

Command:
cat notes.txt

### 5. Copy notes.txt to backup.txt

Command:
cp notes.txt backup.txt

### 6. Show the first 100 lines of logs.txt

Command:
head -n 100 logs.txt

### 7. Show the last 100 lines of logs.txt

Command:
tail -n 100 logs.txt

### 8. Check the disk storage usage of the server

Command:
df -h

### 9. Check the running processes in the system

Command:
ps -ef

### 10. Delete a file called temp.txt

Command:
rm temp.txt


## SECTION 3 – Concept Questions

### 1. What is the difference between > and >> in Linux?

>is used to overwrite the content of a file.

Example:
echo "Hello" > file.txt

>> is used to append content to the end of a file without deleting the existing content.

Example:
echo "Hello" >> file.txt

### 2. What is the purpose of the kill -9 command?

The kill -9 command is used to forcefully terminate a running process in Linux.

Example:
kill -9 1234

### 3. What is the difference between rm and rmdir?

rm is used to remove files or directories.

Example:
rm file.txt

rmdir is used to remove an empty directory only.

Example:
rmdir foldername

### 4. What information does the netstat -tulpn command provide?

The netstat -tulpn command shows active network connections, listening ports, and the processes using those ports in the system.


### 5. What is the purpose of the ping command?

The ping command is used to check the network connectivity between your system and another server or website.

Example:
ping google.com


## SECTION 4 – Scenario Based Questions

### 1. You want to check the current working directory. Which command will you use?

Command:
pwd

### 2. You want to create a directory called devops inside the home directory. Write the command.

Command:
mkdir ~/devops

### 3. You want to check which process is using high CPU in the system. Which command will help?

Command:
top

### 4. You want to check whether your server can connect to google.com. Which command will you use?

Command:
ping google.com

### 5. You want to view the last 50 lines of a log file called application.log. Write the command.

Command:
tail -n 50 application.log
