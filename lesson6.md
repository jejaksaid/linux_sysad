---
### Programs vs Scripts
---

1. which is the difference between binary programs and text based scripts
2. how does the operating system tell the difference
3. how can users tell the difference
4. how are they made

### Compilers

1. what is a compiler
2. why would i want a compiler
3. which compilers should i get

### Building Source Code

1. where can i go to get programs that are distributed ad source
2. how do i build source code programs
3. why would i want to build programs myself
4. how are source code projects installed
5. how do i remove them

### Binary Programs

1. what does a "Hello World" program in C look like
2. how do use the GCC compiler to convert source code to binary
3. how do i use a Makefile to do the conversion
4. how to i run the binary program

code in c:
#include <stdio.h>

int main() {
printf("Hello World\n");
return 0;
}

command: gcc hello.c
-> you have to install the compiler first

### Scripting Languages

1. what does "hello world" look like in perl
2. what does "hello world " look like in python
3. what does "hello world " look line in bash

code in perl: (.pl)
#! /usr/bin/perl
print "Hello World!\n";

code in python: (.py)
print("Hello World!")

code in bash: (.sh)
echo Hello World!

### STDIN, STDOUT, STDERR

1. how do i use a text file for the input to a program
2. how do i save the output from a program into a text file
3. how do i save the standard error from a program in a text file
4. what do i do if i do not want to display or save standard error or standard out

commands:
cat > newfile.txt
cat < hello.c > newhello.c

### Using Pipes

1. which character is the pipe? how do i type the pipe char
2. how do i use the pipe send output from one program into the input of another program
3. can i use the pipe more than once in a single command line

commands:
./hello
./hello | wc
ls -al | wc
ls -al | sort | wc

### File Types

1. what types of files exist on linux machine
2. in dir listings, what do "d", "l", "b", and "c" stand for
3. do file extensions mean anything
4. what does the file command tell me
5. what is an ELF file -> linux file format for binary

### Links

1. what is a symbolic link
2. what is a hard link
3. what is the difference between symbolic links and hard links
4. what happens when i edit a symbolically linked file
5. what happens when i edit a hard linked file

commands:
ln -s hello hello2
ln hello hello3
unlink hello
