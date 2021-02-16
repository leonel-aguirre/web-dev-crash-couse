# WEB DEV CRASH COURSE
This repository contains the code and documentation of a course on how to learn web development.  

# Table of Contents
- [Requirements](#requirements)
- [Basic Terminal Usage](#basic-terminal-usage)

# Requirements
- [Git.](https://git-scm.com/)
- A code editor ([VS Code](https://code.visualstudio.com/) is recommended).  

# Basic Terminal Usage
Learning how to use your terminal will help you speeding up tasks as it gives you the ability of do **"whatever you want"** by inputting commands inside a single window.

## Terminal Commands [WINDOWS]
### Change directory
Whenever you want to move through your file system you will need to use `cd` followed by the path you want to move to; this path can either be **absolute** or **relative**. If you want to go back to the previous directory you should use `..` as your path.

**Command:**  `cd`
**Example:**  `cd "path/to/directory/"`

### List the files of a directory
To see all the files within your current path you can use either the `dir` or the `tree` commands, `tree` will list all files and directories including subdirectories unlike `dir` which will be limited only to the files of the current directory unless you add the parameter `/S` to the command.

**Command:**  `dir` or `tree`
**Example:**  `dir` or `tree`

### Copy files
The `copy` command will take the files you specify and copy them into a desired path. You can also tell explicitly which files to copy, for instance, if you want to copy all **.pdf** from your current path you should write `*.pdf` as the origin.

**Command:**  `copy`
**Example:**  `copy "file.txt" "another/path"`

### Move files
Similarly as the `copy` command, you can use `move` to take files and place them into the path you want, the difference is that `move` will not copy the files.

**Command:**  `move`
**Example:**  `move "file.txt" "another/path"`

### Rename files

**Command:**  `rename`
**Example:**  `move "file.txt" "another/path"`