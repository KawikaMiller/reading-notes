# Practice in the Terminal

These notes will help to refresh and maintain my working knowledge about using the command line / terminal during software development.

## Command Line

The command line should not be thought of as a 'replacement' of a GUI but rather a supplemental tool that we can use with a GUI.

Terminals have a `shell` which defines how the termial behaves and looks after running/executing commands. There are a lot of different shells available but the most common is called `bash` which stands for *Bourne again shell*.

## Basic Navigation

We can use commands like:

- **pwd** : 'print working directory' which tells you what your present working directory is.

- **ls** : 'list' which lists all the visible contents of a directory

### Paths

File systems are a hierarchial structure and at the very top of the hierarchy is what's called the *root* directory - which is denoted by a single forward slash `/`. From there, there are subdirectories may contain files and/or other subdirectories, which may then also contain files and/or other subdirectories, etc.

**Absolute Paths** specify a location in relation to the root directory. Easily identified because they always begin with a forward slash `/`

**Relative Paths** specify a location in relation to where we currently are in the system. These will not begin with a slash/

- `~` is a shortcut for your home directory
- `.` is a reference to your current directory
- `..` is a reference to the parent directory

---

We can also use the command `cd` to *change directories*.

For example we can run `cd ../` to move up/back one directory. 

```
$ pwd
users/myUserName/myDocuments
$ cd ../
users/myUserName

```

## More About Files

Everything is a file.

With OS's like Windows, files have a file extension that denote what kind of a file it is, such as `.png`, `.txt`, `.exe`, etc.

Linux is a *extensionless system* and it determines what kind of a file it is by looking inside of the file. So even if you rename `myPfp.jpg` to `myPfp.txt`, linux will still treat that file as an image.

If for some reason a file does not have a file extension, (e.g. `myPfp`), we can use the `file` command to determine what type of file it is.

```
file [path]
```

### Case Sensitivity

Linux is also **case sensitive**, which means that `file.txt` and `FILE.txt` are treated as two separate files.

This case sensitivity also carries over to the command line, for example the command `ls` has two options `-s` and `-S` which both do different things.

### Spaces in File Names

Having spaces in file names can also be problematic because of how the command line functions. 

Remember that spaces in the command line are effectively like a period in written text in that they separate statements.

For example, if we have a directory named `Holiday Photos` and we try to run the command

`cd Holiday Photos`

the command line will try to change directories into `Holiday` because its treating `Holiday` and `Photos` as two separate statements.

In order to circumvent this we can either wrap `Holiday Photos` in quotes or use an escape character, `\`.

So either `cd 'Holiday Photos'` or `cd Holiday\ Photos` would be a valid way to access that directory

### Hidden Files and Directories

A file or directory can be made hidden by giving it a `.` at the start of its name. If we want to make it un-hide it, we can just remove the `.` from the name.

However, if we still want to access a hidden file we can use the option `-a` when we use the `ls` command, (e.g. `ls -a [path]`).

## Manual Pages

We can use the `man [command]` to essentially get the documentation for any given command. This will return information like the various options that we can invoke with the command and a brief description of what the command does.

We can also use the command `man -k [search term]` to search within various manual pages for whatever search term you give it. For example, maybe you know that you want to delete or remove a file but you're unsure what command to run in order to accomplish that. You can run `man -k remove` and it will return manual pages that contain the word 'remove' - which should help to put you on the right track.

If you want to search within a manual page this is also possible. To do this, whilst you are in the particular manual page you would like to search press forward slash '/' followed by the term you would like to search for and hit 'enter' If the term appears multiple times you may cycle through them by pressing the 'n' button for next.

### Longhand vs. Shorthand Command Options

Some command options have a longhand and shorthand version, for example

```
$ ls -a
$ ls --all
```
Are both the same option. Note that when you use the long hand version of an option you must use two dashes `--` and when you use the short hand you must use one dash `-`.

When we use a single dash we may invoke several options by placing all the letters representing those options together after the dash.

## File Manipulation

There are various commands we can use to manipulate our file heirarchy.

- `mkdir` : 'Make Directory`
	- `mkdir [options] <Directory>
- `rmdir` : 'Remove Directory'
	- `rmdir [options] <Directory>
*There is no "undo" when we use the command line so be incredibly careful when you run these commands
- `touch` : Creates a blank file
	- `touch [options] <filename>
- `cp` : Copies a file or directory
	- `cp [options] <source> <destination>
- 'mv' : Moves a file or directory
	- `mv [options] <source> <destination>
*We can also use `mv` to rename a file. Normally mv will be used to move a file or directory into a new directory. As we saw on line 4 above, we may provide a new name for the file or directory and as part of the move it will also rename it. Now if we specify the destination to be the same directory as the source, but with a different name, then we have effectively used mv to rename a file or directory.
- `rm` : Removes a file and non-empty Directories
	- `rm [options] <file>`
*If we use the `-r` option with the `rm` command it will remove the directory and all files/directories contained within it.

## Cheat Sheet

[Command Line Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

## Things I Want To Know More About
n/a