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

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do. (Use the 8 items above and add a couple of your own.)
 
> > "pwd - print working directory
ls - list contents of directory
mkdir - make directory (creates a new directory in the working directory)
touch - creates a new file inside the working directory.
cd  - change directory (into the directory you specify)
cd .. - go back up one
cp copies files
mv moves and renames files
rm file - remove file
rm -r directory/ - remove a directory
ps - process listing
.  - current directory
.. - previous directory
cat - command outputs the contents of a file to the terminal.
more - show me the content of something
chmod - change user rights


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

> > ls      : List contents of current directory
> > ls -a   : Show hidden directories (lists ALL hidden files and directories)
> > ls -l   : Shows information about the directories and files (permissions and date)
> > ls -lh  : Lists files and directories (permissions, human readable size, time)
> > ls -lah : Show all hidden files and directories with intense details with in  human readable format.
> > ls -t   : Orders files and directories by the time they were last modified
> > ls -Glp : Highlights the directories (G) and accents directories  with their / (p) while showing more detailed information of all files and directories




---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -m:    Displays the names as a comma-separated list.
ls -n: 	      Displays the long format listing, with GID and UID numbers.
ls -o: 	      Displays the long format listing, but excludes group name.
ls -R: 	      Displays subdirectories as well.
ls -p: 	      Displays directories with /
ls -lh:       Shows sizes in human readable format.
ls -F :       Shows the directories by adding their "/"

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > To build and execute commands from standard input. It converts input from standard input into arguments to a command

> > ex. : standard input is piped to xargs and the mkdir command is run for each argument, creating three folders.

> > echo 'one two three' | xargs mkdir
> > ls
> > one two three
