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

* show current working directory path: pwd
* create a directory: mkdir
* delete a directory: rm -r
* create a file with 'touch': touch <filename>
* delete a file: rm <filename>
* rename a file: mv <oldname> <newname>
* list hidden files: ls -a
* copy file from one directory to another: cp <filename> <directory/>
* append std output from file on left to file on right: <filename*> <filename>
* search files for pattern and return results: grep "pattern" <filename>

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

* 'ls': lists all files and directories within current working directory
* 'ls -a': lists all files and directories within current working directory, including hidden files
* 'ls -l': lists all files and directories in current working directory in long format
* 'ls -lh': lists all files and directories in current working directory in long format, using unit suffixes
* 'ls -lah': lists all files and directories in current working directory including hidden files, in long format, using unit suffixes
* 'ls -t': lists all files and directories in current working directory sorted by most recently modified'
* 'ls -Glp': lists all files and directories in current working directory with colorized output and a fwd slash after each directory name  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

* 'ls -C': output in columnar format
* 'ls -d': lists only directories
* 'ls -r': lists files in reverse order
* 'ls -R': includes subdirectories
* 'ls -u': sorts by file access time
* 'ls -x': displays files as rows

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > 'xargs' funnels standard input into command line tools. By default, without argument, xargs runs this input into the "echo" command, but other tools can be specified. For example, xargs is commonly used with "find" and "rm" (remove), like this:

> > find . -name "*.txt" | xargs rm

> > this command will find all files in the current directory (.) with '.txt' in the name, and then xargs will remove those files

 

