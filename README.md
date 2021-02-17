# WEB DEV CRASH COURSE
This repository contains the code and documentation of a course on how to learn web development. Some of the topics of this course are based on the [**WEB DEVELOPER ROADMAP 2021**](https://github.com/kamranahmedse/developer-roadmap) by [@kamranahmedse](https://github.com/kamranahmedse)

# Table of Contents
- [Requirements](#requirements)
- [Basic Terminal Usage](#basic-terminal-usage)
- [Tasks](#tasks)

# Requirements
- [Git.](https://git-scm.com/)
- A code editor ([VS Code](https://code.visualstudio.com/) is recommended).
- A [GitHub](https://github.com) account.

# Basic Terminal Usage
Learning how to use your terminal will help you speeding up tasks as it gives you the ability of do **"whatever you want"** by inputting commands inside a single window.

## Terminal Commands [WINDOWS]
### Change directory
Whenever you want to move through your file system you will need to use `cd` followed by the path you want to move to; this path can either be **absolute** or **relative**. If you want to go back to the previous directory you should use `..` as your path.

**Command:**  `cd`
<br>

**Example:**  `cd "path/to/directory/"`
<hr>

### List the files of a directory
To see all the files within your current path you can use either the `dir` or the `tree` commands, `tree` will list all files and directories including subdirectories unlike `dir` which will be limited only to the files of the current directory unless you add the parameter `/S` to the command.

**Command:**  `dir` or `tree`
<br>

**Example:**  `dir` or `tree`
<hr>

### Print text, create and overwrite files
The `echo` command is used to print text into the terminal, just run `echo` followed by the text you want to print. Also you can write text into a file using `echo` even though the file doesn't exists yet or in the case it does the file will be overwriten.

**Command:**  `echo`
<br>

**Example:**  `echo hi there!`, `echo hi there > newFile.txt`
<hr>

### Copy files
The `copy` command will take the files you specify and copy them into a desired path. You can also tell explicitly which files to copy, for instance, if you want to copy all **.pdf** from your current path you should write `*.pdf` as the origin.

**Command:**  `copy`
<br>

**Example:**  `copy "file.txt" "another/path"`
<hr>

### Move files
Similarly as the `copy` command, you can use `move` to take files and place them into the path you want, the difference is that `move` will not copy the files.

**Command:**  `move`
<br>

**Example:**  `move "file.txt" "another/path"`
<hr>

### Rename files
With `rename` you can change the name and extension of a file.

**Command:**  `rename`
<br>

**Example:**  `rename "file.txt" "file.bat"`
<hr>

### Delete files
To delete a file from the file system you can use the `del` command.

**Command:**  `del`
<br>

**Example:**  `del "file.txt"`
<hr>

### Create a directory
With the `md` command you can create a new directory in the desired location.

**Command:**  `md` or `mkdir`
<br>

**Example:**  `md "newDirName"`
<hr>

### Remove a directory
To delete a directory use the `rd` command followed by the name of the directory you want to remove. The `rd` command without parameters will only delete empty directories, if you want to remove the whole directory including files inside you need to use the `/S` parameter.

**Command:**  `rd` or `rmdir`
<br>

**Example:**  `rd "dirToRemove"`
<hr>

### Print network adapter information
There will be cases where you need to know your local ip address, so, the `ipconfig` command will show information of your computer's network adapter including the local ip address.

**Command:**  `ipconfig`
<br>

**Example:**  `ipconfig`
<hr>

### Clear the terminal
As commands are executed your teminal will carry a lot of data. To clear the terminal you can use the `cls` command.

**Command:**  `cls`
<br>

**Example:**  `cls`
<hr>

### Clear the terminal
As commands are executed your terminal will carry a lot of data. To clear the terminal you can use the `cls` command.

**Command:**  `cls`
<br>

**Example:**  `cls`
<hr>

### Get help
Whenever you want to get information about a certain command you can use the `help` command followed by the command you want to know more about. Also, if you run just the `help` command it will show a list of supported commands for Windows cmd.

**Command:**  `help`
<br>

**Example:**  `help rd`, `help mkdir`, `help`

## ⚠⚠⚠ Task ⚠⚠⚠
By the end of this section you must complete the following tasks:
- [basic terminal usage](#1.basic-terminal-usage) task.

# Tasks
In order or getting a better understanding of the topics seen is advisable to carry out the following tasks:

## 1.Basic terminal usage
The goal of this task is to get used to terminal commands.

### 📋 Instructions 📋
1. Using only the terminal, create the following file structure:
```
│   fileX.txt
│   fileY.txt
│   fileZ.txt
│
├───dir1
│       fileA.txt
│
├───dir2
│       fileB.txt
│
└───dir3
        fileC.txt
```
2. Move `fileY.txt` into `.\dir2\dir2.1` and `fileZ.txt` into `.\dir3` leading to the following file structure:
```
│   fileX.txt
│
├───dir1
│       fileA.txt
│
├───dir2
│   │   fileB.txt
│   │
│   └───dir2.1
│           fileY.txt
│
└───dir3
        fileC.txt
        fileZ.txt
```
3. Delete `dir2` and `dir3` including the files inside them and create a new file at the root with your local ip as name as following:
```
│   192.168.1.182.txt
│   fileX.txt
│
└───dir1
        fileA.txt
```