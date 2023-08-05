# Bash_registro

hello, this is my bash log, here we will learn how to use bash with Scripting, with the git bash terminal

## Introduction

First we need Git Bash (a terminal where we put the Scripts, generally if the scripts are used in Linux terminals.
However we will use git bash in Windown, so it does not matter and it is not necessary to use Linux.

### We need previous knowledge of commands:
```
ls
mkdir
cd
echo
nano
chown
```
We'll automate a simple process where every time we read a new book, we'll run the script and it will ask us for details (title and author), then take our answers, and add them to a list of books (a file called books.txt ), and send it to us by email. All by running a single command: ``` ./myScript.sh ```

## This is what we'll do

What we will do is write the script, and when executing it we will only use bash ``` myScript.sh ```

1. Let's create a text file called ``` books.txt ```
2. we will write in the bash ``` myScript.sh ```
3. we will make a directory ``` mkdir scripts ```
4. then we will ``` cd scripts ```
5. we will ``` touch books.txt ```
6. we have to put ``` echo ``` " frankenstein - Mary Shelly " ```>``` ``` books.txt ```
7. we will ```chown <user>:<user> books.txt```
8. we will put ``` nano scripts ```

## Dentro del comando ``` nano scripts ```
``` 
#!/bin/bash
echo "este es el tuto de bash"
sleep 5
echo "como te llamas?"
read nombre
echo 'tu te llamas:' ${nombre}
```
and to reflect the commands or the text lines of ``` nano ``` we will put a ``` ./myScript.sh``` to be able to reflect or answer everything or you can put ``` bash myScript.sh```
