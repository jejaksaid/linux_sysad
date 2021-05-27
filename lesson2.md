---
### Home Directory
---

1. how do i bring up a terminal window
2. what files are in my home directory
3. how do i know what directory i am in
4. what does my prompt tell me

commands:
pwd =>
ls =>
-l =>
-al =>

### Environment Variables

1. what are environment variables
2. does it matter what my environment is
3. how do i see environment variables
4. how do i change my environment

commands:
env =>
echo $HOME =>
cat .bashrc =>
cat .bash_profile =>

### Terminal Redirection

1. when using the terminal, what do >, <, and >> mean?
2. how are variables used in commands
3. what is the backtick and how do i use it

commands:
time =>
date =>
date > saved_date.txt
cat saved_date.txt
date >> saved_date.txt
cat saved_date.txt
date +%d
date +"%d"
date + "%Y%d"
date + "%Y%m%d"
date + "%Y-%m-%d"

### Manual Pages

1. how do i find information about commands
2. what information is provided by manual pages
3. how do i get out of this man command
4. what if there are C functions and programs with the same name

commands:
man date =>
man time =>

### File Management

1. how do i create files
2. how do i edit files
3. what information does the file system keep on each file
4. how do i move a file
5. how do i rename files
6. how do i copy files
7. how do i delete files

commmands:
rm =>
mv =>
touch =>
unlink =>
mv namefile Dir/ =>
nano =>
cat =>

### Searching and Editing Files

1. how do i file files containing some string of characters
2. how do i display the contents of a file
3. how do i know what type of file a file is
4. how do i edit a text file

commands:
grep something _ =>
grep some _ =>
grep some _/_

### Directory Management

1. how do i create directories
2. how do i move directories
3. how do i rename directories
4. how do i delete directories

commands:
mkdir =>
olddir =>
mv newdir/ olddir =>
mv olddir/ Desktop =>
rmdir Desktop/olddir/ =>
rm Desktop/olddir/

### Links

1. what are hard links
2. what are symbolic links
3. are symbolic links the same as windows shortcut
4. how do i create links
5. how do i remove links

commands:
ln newfile.txt newfile2.txt
ln -s newfile.txt newfile3.txt
echo hello >> newfile.txt

### Absolute vs Relative Path

1. what is an absolute path
2. what is a relative path
3. what is the difference between a relative and absolute path
4. can absolute and relative paths be used interchangeably

commands:
pwd =>
ls -l /home/said/
