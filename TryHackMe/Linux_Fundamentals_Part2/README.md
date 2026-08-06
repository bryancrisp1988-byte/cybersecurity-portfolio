# Linux Fundamentals Part 2

Platform: TryHackMe

## Intro

This write‑up documents my completion of TryHackMe’s Linux Fundamentals Part 2 room, focusing on permissions, users, groups, processes, and services.

## Objective

* Learn fundamental skills in being able to log in and control the terminals of remote machines.
* Unlocking the potential of the first few commands by using flags, switches, and understanding that arguments are highlighted by hyphens and certain flags and switches.
* Advancing knowledge of filesystems to perform more useful commands like copying and moving files.
* Discovering how access to files and folders is managed and how we can determine our access.
* Understand permissions 

## Key Skills Learned

* How to use Secure Shell/SSH protocols to log into a Linux machine.
* Understanding and using commands for copying, moving, re-moving files.
* Advancing my use of commands by providing flags & switches & where I can go to learn about these for each command (man pages). 
* Understanding the file system's basic numeric format.
    * R=read=4,
    * W=write=2,
    * X=execute=1.
* Brief introduction to file permissions & switching users.

## Commands Practised

## Navigation & Listing
* 'ls'
* '-a'
* '--help'
* '.'
* 'man'
* '-h'

### File & Directory Managment

* 'touch'
* 'mkdir'
* 'cp'
* 'mv'
* 'rm'
* 'file'

### System Directories
  
* /etc
* /var
* /root
* /tmp

## Processes

Process

## Command Explanations

ls        - List files in the current directory  
-a        - Show hidden files  
--help    - Show available options for a command  
.         - Current directory  
man       - Open the manual page  
-h        - Human-readable output  
touch     - Create a file  
mkdir     - Create a directory  
cp        - Copy a file  
mv        - Move a file  
rm        - Remove a file  
file      - Determine the type of a file  
/etc      - System configuration files  
/var      - Variable data  
/root     - Home directory for the root user  
/tmp      - Temporary storage  
process   - Viewing running processes

## Screenshots

Uploaded.

## Tasks Completed

* Explored the manual page of the Ls command.
* Basic navigation of the manual page.
* Finding and identifying a flag and displaying the output in a 'Human-readable' way.
* Understanding and creating a file name.
* Finding and understanding a file type and its use in the home directory.
* Understanding and moving a file to the directory folder.
* Identifying the content on the 'Myfile' and showing its display.
* On the deployable machine understanding who the owner of 'important' is.
* Understanding and displaying the command to switch to 'user2'.
* Outputting the content of 'important' and displaying its flag.
* Displaying the directory path logs are stored.
* Understanding the /tmp root directory is similar to RAM.
* Understanding the home directory of the root user.

## Reflection

This room improved my confidence with Linux permissions and user management, and I now feel more comfortable navigating and administering Linux systems.

## Status

Complete
