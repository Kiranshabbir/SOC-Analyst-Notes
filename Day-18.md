# Day 18 - File permissions in Linux
Date: Nov 13, 2026


## 1. What I learned
- Every file has 3 permission groups: owner, group, and others.
- Each group can have read (r), write (w), and execute (x) permission.
- chmod command is used to change permissions of file or folder.
- chown command is used to change the user and ownership of file.


## 2. What I did
- I practiced these commands in Kali Linux: chmod, chown.
- I made myfile.txt and ran ls -l. It showed: -rw-rw-r--
- I ran chmod +x myfile.txt and ran ls -l again. It showed: -rwxrwxr-x
- I ran whoami and saw my username: kali
- I ran chown $(whoami) myfile.txt to confirm I own the file.
- I practiced chmod and chown in Kali Linux.
- I completed OverTheWire Bandit Level 5.


## 3. New words
- chmod: change mode
- chown: change owner 
- r: read 
- w: write 
- x: execute 


## 4. What was hard
- Nothing was hard.


## 5. Explain in 2 sentences
- In Linux, I use the chmod command to change permissions of the files and chown command to change ownership of the files. 
