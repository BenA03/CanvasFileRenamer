# CanvasFileRenamer

## Overview

This is a tool intended for instructors of the Computer Methods in the Humanities course to quickly rename student submission filenames downloaded from Canvas. The program is written in Java and runs from the command line.

## How to run this program

In order to use this program, it is necessary to [download Java](https://www.java.com/en/download/manual.jsp).

To start the program, navigate to the directory containing `FolderScript.java` using the command line. Once you are there, input the following commands:

1. `javac FolderScript.java` will compile the program, and
1. `java FolderScript` will run it 

## How to use the program

Once the program is run in the command line, you will be prompted to enter some information
about the directory you want to edit. Provide either an absolute or relative path to this folder,
and the confirm that the files displayed in the terminal are the ones you want to edit.

**Note: this program does not create a copy of the directory before altering filenames, so be sure you are operating over
the correct folder, because the changes will be difficult to undo.**

After the filenames are edited, warning messages will appear in the terminal if a revised filename
contains characters or patterns that break filenaming conventions, like containing certain special characters or
starting with an uppercase letter.

When the program is finished, the original directory should contain copies of the files with leading Canvas
metadata stripped out of the filename.