# TryHackMe — Linux Fundamentals Part 1

## Objective
Learn basic Linux navigation commands and locate hidden files on the system.

## Commands Used
- `pwd`
- `ls -la`
- `find / -type f -name "mission_brief.txt" 2>/dev/null`
- `cat <file>`

## Process
1. Confirmed current directory using `pwd`.
2. Listed all files, including hidden ones, using `ls -la`.
3. Used `find` to locate `mission_brief.txt` across the filesystem.
4. Found the file at:  
   `/home/ubuntu/Documents/.research/archive/mission_brief.txt`
5. Read the file using `cat` to retrieve the mission flag.

## Lessons Learned
- Hidden files begin with a dot (`.`).
- `find` is essential for locating files anywhere on the system.
- Linux navigation requires understanding directory structure and absolute paths.

## Screenshots
(Add your screenshots here)

## Summary
This task strengthened my Linux fundamentals and taught me how to navigate, search, and read files effectively — skills essential for cybersecurity work.
