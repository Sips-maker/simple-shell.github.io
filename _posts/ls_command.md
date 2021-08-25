##  What happens when you type `ls -l *.c` in the shell

Linux is one of the most popular Unix based operating systems. One amazing feature of the Linux operating system is the Command Line Interface (CLI) which allows users to interact with their computer from a shell. A shell is the command interpreter between the user and the computer, when you write a command on the terminal, the shell translates the message to the computer and then the command is executed.  

The ls command is one of the many Linux commands that allow a user to list files or directories from the CLI.


---

### The ls Command
ls - lists all files or directories usually in the current working directory
```
ls
```

![IMG_ls](https://user-images.githubusercontent.com/84739465/130857760-584c3367-13e8-42dd-8ea0-965f9236038f.jpg)

ls -l - lists all files in long format showing the permissions, size, modified date and time, file or folder name and owner of file
```
ls -l
```

![IMG_ls-l](https://user-images.githubusercontent.com/84739465/130858275-3b8589db-49a6-4e36-a2c0-e48c01940af2.jpg)

(*) - is usually used to find a match in the current working directory

.c - shows or lists files with the extension .c
```
ls *.c
```

![IMG_ c](https://user-images.githubusercontent.com/84739465/130857560-53a1e8d0-5768-4417-8f9c-81663c7b40cb.jpg)

In the end  the command will display a list of all the files with a specific occurrence, which is all the files ending with the extension .c. All the other files will be ignored, this is really useful when you are trying to search for specific files.

