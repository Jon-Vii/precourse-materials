### What are the top 20 commands for mac Command Line Interface (CLI)?

1. cd: changes the working directory you're currently in. Example: cd "path/to/directory/"

2. ls: lists the contents of the directory you're currently in. ls -l gives more info with info on permissions, owner and date of creation for each file.

3. open: ope "filename" will open a file with the appropriate app.

4. cp: cp "filename" "newfilename" copies file to a copy with the path, filename and extension defined in the newfilename.

5. mv: mv "filename" "path/to/new/file/location" same format as cp, moves a file to a new location.

6. touch: creates a blank file

7. mkdir: mkdir "path/to/new/directory/ makes a new directory

8. rmdir: rmdir "path/to/directory" removes a directory

9. rm -R "path": removes nested directories

10. sudo: executes command with superuser privileges

11. top: lists actively running computer processes. such as memory, CPU and disk utilization, per app.

12. q: quits subscreen, same effect as Control + C.

13. clear: removes all previously typed commands from the terminals view.

14. ditto "source" "dest": copies the contents of one directory into another. -V flag adds verbose output when running.

15. whatis "command": gives short description of given command.

16. man "command": shows manual page for a longer description of given command.

17. exit: closes out terminal session.

18. shortcuts run "Name of Shortcut": runs specified Apple Shortcut

19. tmutil startbackup: starts backup snapshot for mac using timemachine.

20. killall AppName: forcequits specified application



### What is a terminal? A CLI? Why are they synonymous?

A terminal used to mean a device by which through the user would interact with a computer. A console is a kernel implemented terminal, directly connected to a machine. A command line interface is an interface of the console by which the user types a command that is then executed by the machine.

### What's the difference between Bash and Zsh?
Zsh contains the features of Bash, but extends it to include: spell-checking, the ability to watch for logins/logouts, some built-in programming features like bytecode, scientific notation support in syntax, floating-point arithmetic support, and more.

### What is the difference between Terminal, Console, Shell, and Command Line?
To add to the previous answer, a Shell is an extension of the CLI environment adding new features and functionality.