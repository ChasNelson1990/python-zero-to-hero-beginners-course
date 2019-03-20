# Shells and Command Line Interfaces

## Objectives

* To introduce the concept of a shell
* To explain how to shell relates to programs and scripts

## Background

Computers require a way for users to interact. Most computers use a Graphical User Interface (GUI). These are easy to learn and are human friendly. But GUIs rely on the fact that the user will want to do simple tasks and that there is one specific program to accomplish that task.

Another common interface is a **shell**. A shell is a program that runs other programs and is controlled through a **command-line interface** (CLI). Think of computer hackers in Hollywood movies - the green text on a black background is their shell and it provides them with access to a lot of tools.

## Accessing a Shell

* *Windows:* The Windows shell is called the *command prompt*. Open the menu (Windows key) and starting typing "command prompt". A small window with a black background and white cursor will appear. Type `HELP` to see the basic commands available.
* *MacOS:* You can access shell using application `Terminal`. Type `CMD+Space` to find it with Spotlight. Once opened `man <COMMAND>` will provide the manual page for any command.
* *Linux:* You may have multiple "terminal emulators" on a Linux system and you probably have your favourite already. As with OsX, `man <COMMAND>` will give you information about a command.

## Running Programs from a Shell

Once you've opened a shell you should notice that your line starts with a "prompt", e.g. `C:\>`. Because different operating systems will use different text for the prompt, we will always use `$` to indicate the prompt. If we use the shell in an exercise *do not type the prompt* only the following command.

From the shell you can run a variety of programs by typing a given **command** and hitting Enter/Return. Many built-in commands are simple, e.g. `ls`, which lists files in the current directory. But the shell can also run other shells - like the Python or R programming environments. In the worksheet *Files and Directories* you will see examples of three shell commands: `ls`, `cd`, `pwd`.

## The Path

In order for a shell to execute a command, it must know what that command means. Shells accomplish this with a **path** - a list of places to search for commands. You can think of a computer's path as where the computer stores dictionaries of commands.

Once a shell is given a command, it looks in all the locations in the path until it find the command. If found, the command is executed. If not, the shell will print something like `command not found`.
