# Files and Directories

## Objectives

* Understand the terms 'file', 'directory' and 'path'
* Know about the current working directory
* Know how to convert between absolute and relative paths
* See some basic shell commands for files and directories

## Files, Directories and Trees

Information on computers is stored in files and directories, which are managed by the file system and for a branching tree-like organisation structure. Briefly, we can define all these elements as:

* **File System:** the structure used by a computer to *manage* files and directories.
* **File:** the unit in a file system that holds *information*.
* **Directory:** the *structural* unit in a file system that holds files and other directories.
* **Directory Tree:** the overall *branching structure* formed by directories and files managed by the file system.

## Paths and Slashes

Operating systems allow you to access and interact with files and directories through GUIs and through CLIs (see *Shells and Command Line Interfaces*). Here we will introduce how to interact with files and directories through a CLI.

The 'address' of a file or directory is called its **path**. Paths on different operating systems will look different. For example, a user's home directory might look like:

* **Windows:** `C:\Documents and Settings\chas`
* **MacOS:** `/Users/chas`
* **Linux:** `/home/chas`

Note how the slashes, which separate directories and files in the path, go in different directions for different operating systems.

## Root and the Current Working Directory

Whilst navigating around an operating system there are two special directories within a directory tree that are important to understand.

The first, `/`, is the 'root' directory (`C:\` in Windows), i.e. the base of the directory tree. Note that when `/` appears at the start of a path it indicates the root directory but when `/` appears inside a path it separates one directory level from the next.

Second, it is often useful to know the **current working directory**, i.e. where you currently are in the directory tree. The `pwd` (print working directory) command will print to the shell the full path of your current location.

The current directory can also be referred to by `.` and the parent directory (one level up the directory tree) by `..`. We will use both of these to explore absolute and relative paths and the commands `cd` and `ls` below.

## Absolute and Relative Paths

The example home directories above all start with root (`/` or `C:\`) - these are **absolute paths**. However, file systems also understand **relative paths** - paths that do no start with root. For example, if a home directory (which is also the current working directory) contains a subdirectory called `myDirectory` that holds a file called `myFile.csv` then the following both refer to the same file:

* **Absolute path:** `/Users/chas/myDirectory/myFile.csv`
* **Relative path:** `./myDirectory/myFile.csv`

## Navigating the File System

Navigating the file system through a GUI can be quick and easy - the user can see all the subdirectories and files in a directory and clicks to navigate or interact with them. But navigating through a CLI can also be quick - once you know a couple of key commands.

The first of these is the `ls` (listing) command, which will print to shell all subdirectories and files in the current working directory. Here is an example of using `ls` in a user's home folder. (Remember that `$` is the shell prompt)

```sh
$ pwd
```

> /Users/chas

```sh
$ ls
```

>myDirectory &nbsp; &nbsp; myOtherDirectory &nbsp; &nbsp; myFile.csv

The second command for navigating the file system is the `cd` (change directory) command. The `cd` command can be provided with an absolute or a relative path and will change the working directory to that new path. It is possible to use `.` (current directory) and `..` (parent directory) within relative paths. The path provided must exist. Here are three examples of using the `cd` command with the current working directory shown above.

```sh
$ cd ..
$ pwd
```

> /Users/

```sh
$ cd /Users/chas
$ pwd
```

> /Users/chas

```sh
$ cd ./myDirectory
$ pwd
```

> /Users/chas/myDirectory

```sh
$ cd /Users/chas/notADirectory
```

> cd: no such file or directory: /Users/chas/notADirectory
