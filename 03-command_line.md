# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > | COMMAND                            | DESCRIPTION                                          |
> > | ---------------------------------- | ---------------------------------------------------- |
> > | man "command"                      | Shows information about the command                  |
> > | ls folder                          | Shows current working directory path                 |
> > | mkdir "directory"                  | Creates a directory                                  |
> > | rmdir "directory"                  | Deletes a directory                                  |
> > | touch "file name"                  | Creates a file using touch command                   |
> > | rm "file name"                     | Deletes a file                                       |
> > | mv "file name (1)" "file name (2)" | Renames the file                                     |
> > | ls -a                              | Shows hidden files in current directory              |
> > | mv "file name" "directory"         | Moves or copies a file from one directory to another |
> > | cat "file name"                    | Shows the contents of file                           |
> > | ifconfig -a                        | Displays all network interfaces and IP addresses     |
> > | locate "name"                      | Finds files and directories by name                  |
> > | grep pattern file                  | Searches for pattern in file                         |

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > | COMMAND | DESCRIPTION                                                  |
> > | ------- | ------------------------------------------------------------ |
> > | ls      | Shows current directory files                                |
> > | ls -a   | Shows hidden files in directory listing                      |
> > | ls -l   | Lists files in the directory by owner, group name, file size, last modified timestamp, and file name |
> > | ls -lh  | Same as -l (previous command) except the file size is in kilobytes |
> > | ls -lah | Same as -lah (previous command), but includes hidden files   |
> > | ls -t   | Simple file listing (same as ls), but sorted by date & time (newest to oldest) |
> > | ls -glp | Similar to -l, but includes backslashes at the end of directories and excludes file owner information |

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > | COMMAND | DESCRIPTION                                                  |
> > | ------- | ------------------------------------------------------------ |
> > | ls -F   | Flags file name                                              |
> > | ls -d   | Lists only directories                                       |
> > | ls -m   | Comma-separated list                                         |
> > | ls -la  | Lists all files in the long format                           |
> > | ls -go  | Lists files in the directory by file size, last modified timestamp, and file name |

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > The `xargs` command in UNIX is a command line utility for building an execution pipeline from standard input. Whilst tools like [`grep`](https://shapeshed.com/unix-grep/) can accept standard input as a parameter, many other tools cannot. Using `xargs` allows tools like `echo` and [`rm`](https://shapeshed.com/unix-rm/) and [`mkdir`](https://shapeshed.com/unix-mkdir/) to accept standard input as arguments. (George Ornbo | Shapeshed)

 

