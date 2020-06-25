# Read: 02 - The Coder's Computer

- A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a website.

## Features to look for in a text editor

- code completion
    - display possible suggestions based on what you originally typed.
    - Finishes tags, brackets, quotes, etc.

## Syntax highlighting

- takes the text you type, and makes it more noticeable by colorizing the text.
- Color coordinated so easier to read and look up mistakes

## a nice variety of themes (to reduce eye strain and fatigue)

- allow you to change the color of the background of your text editor, the series of colors in your text, and sometimes themes will affect other aspects of your text editing software as well.
- web developers use a dark background and brightly colored text. This combination seems to be easier on the eyes—but there are other themes to choose from as well.

## the ability to choose from a healthy selection of extensions available when you need them

- like plugins for your text editor, that allow you to have superpowers that you wouldn’t have otherwise.

### Please make sure that when you’re saving your file, that they have the appropriate extension at the end of the file names. 

- ## For example, your main HTML file should be called, “index.html.” Your CSS file should be called something like “style.css.” The filename isn’t as important as the extension (the “.html” and the “.css”).

## The Difference Between Text Editors and IDEs (Integrated Development Environment)

## IED

- a text editor, a file manager, a compiler, and a debugger all in one software package

## Command Line

- is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text

## Basic Navigation

### pwd

- which stands for Print Working Directory
- It tells you what your current or present working directory is

### The command for this task is ‘ls’

- It's short for list
- single command line option ( -l ) which indicates we are going to do a long listing

## Absolute and relative. Whenever we refer to a file or directory we are using one of these paths

- ### Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

- ### Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash

### ~ (tilde)

- This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

### . (dot)

- This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).

### .. (dotdot)

- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

### In order to move around in the system we use a command called ‘cd’ which stands for change directory

## Going over commands and advice

### pwd - Print Working Directory - ie. Where are we currently

### ls - List the contents of a directory

### cd - Change Directories - ie. move to another directory

### Relative path

- A file or directory location relative to where we currently are in the file system.

### Absolute path

- A file or directory location in relation to the root of the file system.

### File

- obtain information about what type of file a file or directory is.

### ls -a

- List the contents of a directory, including hidden files.

### Everything is a file under Linux

- Even directories.

### Linux is an extensionless system

- Files can have any extension they like or none at all.

### Linux is case sensitive

- Beware of silly typos.

[Back to Main](README.md)