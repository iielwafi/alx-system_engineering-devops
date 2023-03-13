# 0x00 Shell Basics

## Resources

- LinuxCommand.org [What is "the Shell"?](http://linuxcommand.org/lc3_lts0010.php).
- [Read the Manual](http://linuxcommand.org/lc3_man_pages/man1.html).
- [Keyboard Shortcuts for Bash](https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/).
- [Understanding what the shell is](https://allthings.how/what-is-the-default-shell-in-linux-called/)
- [User Interfaces in detail](http://theteacher.info/index.php/systems-software/notes/4623-types-of-user-interface)
- [All about the Shells](https://mindmajix.com/shell-scripting-tutorial)
- [Linux commands handbook](https://bjpcjp.github.io/pdfs/devops/linux-commands-handbook.pdf)
- [Linux commands cheat sheet](http://cc.iiti.ac.in/docs/linuxcommands.pdf)
- [Linux terminal starter guide](https://www.howtogeek.com/140679/beginner-geek-how-to-start-using-the-linux-terminal/#:~:text=Launch%20a%20terminal%20from%20your,distributions%20use%20bash%20by%20default.&text=Press%20Enter%20after%20typing%20a,have%20file%20extensions%20on%20Linux.)
- [Getting started with Shell Scripting](https://www.guru99.com/introduction-to-shell-scripting.html)
- [Linux is amazing](https://www.comparitech.com/net-admin/linux-shell-getting-started/)
- [Shell Scripts are awesome](https://dev.to/dechamp/bash-scripts-are-awesome-13m3)
- [Shell scripting crash course](https://www.freecodecamp.org/news/shell-scripting-crash-course-how-to-write-bash-scripts-in-linux/)

## Tasks

0. [Where am I?](./0-current_working_directory) : A script that prints the absolute path of the current working directory.
1. [What's in there?](./1-listit) : A script that displays the contents of your current directory.
2. [There is no place like home](./2-bring_me_home) : A script that changes the working directory to the user's home directory.
3. [The long format](./3-listfiles) : A script that displays the current directory contents in a long format.
4. [Hidden files](./4-listmorefiles) : A script that displays the current directory contents including hidden files.
5. [I loce numbers](./5-listfilesdigitonly) : A script that displays the current directory contents, using long format, while displaying group IDs in numeral and show hidden files.
6. [Welcome my_first_directory](./6-firstdirectory) : A script that will create a directory named `my_first_directory` in the `/tmp/` directory.
7. [Betty in my_first_directory](./7-movethatfile) : A scipt that will move a file called `betty` from home to the new directory created above.
8. [Bye bye Betty](./8-firstdelete) : A script that will delete file `betty` from the new location.
9. [Bye bye my_first_directory](./9-firstdirdeletion) : A script that will delete the directory `my_first_directory` that is in the `/tmp/` directory path.
10. [Back to the future](./10-back) Change working directory to the previous one.
11. [Lists](./11-lists) List all files (*even ones with names beginning with a period character, which are normally hidden*) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12. [File type](./12-file_type) A script that prints the type of the named file `iamafile`. The `iamafile` will be in the `/tmp/` directory when we will run your script.
13. [We are symbols, and inhabit symbols](./13-symbolic_link) Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.
14. [Copy HTML files](./14-copy_html) Create a script that copies all `html` files from the current working directory to the parent working directory while only copying files that did not exist.
