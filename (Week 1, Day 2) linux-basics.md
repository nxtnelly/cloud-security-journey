Linux commands I learned and what they do

sudo apt update: updates the list of available packages and their versions
sudo apt install: downloads and installs an actual software package onto your system
whoami: shows who's currently logged into the terminal session
ls: lists all files that the folder contains
- Adding a folder name or path will print that folders contents (ex: ls bin/)
- man ls: shows all different options with ls cmd
- ls -l: shows all files in a long listing format
- ls -a: doesn’t ignore entries starting with a dot
- ls -al: long format of all files, including files that start with a dot

Ctrl + L: clear space
cd: used to change the current working directory
- There’s no man page for the cd cmd, only “help cd” works
- cd ..: to go back one level of directory
- cd../../..: the one slash means go back two levels
mkdir: used to create one or multiple folders, and even nested folders
- mkdir -p: also used to create nested folders

- mkdir ~/: add folder in home directory
rmdir: remove/delete empty directory
rm: delete files permanently
- rm -v: can delete multiple files at once
- rm -r: remove directory and all files/folders nested in it
- rm -ri: asks if you want to descend into that directory, asks if you want to remove each individual file, then asks if you want to remove the directory as a whole
touch: used to create empty files
cp: copy a file 
- cp -r: to copy the whole folder contents

mv: used to move files between directories and/or rename files 
chmod: change the permissions of a file or directory
- Specify the who using the following values:
U: user (owner of file)
G: group (members of group the file belongs to)
O: others (the “world”)
A: all of the above

- Next, tell chmod what we’re doing using the following characters:
-: (minus sign) removes the permission
+: (plus sign) grants the permission
=: (equal sign) set a permission and removes others

- Finally, the “which” values are:
R: the read permission
W: the write permission
X: the execute permission
Sudo (short for super user do): used to run a command as root
Can run commands as the root user (with elevated permission) using your user’s password
apt update: updates the list of available packages and their versions
apt install:downloads and installs an actual software package onto your system
putting -v after using any command tells you what is being done
root user account is locked, you can’t log into it
