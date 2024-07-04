Pipex

Overview :

Pipex is a project designed to mimic the behavior of the shell pipe (|). This project involves creating a program that replicates the functionality of piping between commands, allowing the output of one command to be used as the input of another.
Features

-   Replicates shell piping functionality.
-   Handles multiple commands and arguments.
-   Manages file input and output redirection.

Prerequisites
-   A Unix-like operating system.
-   GCC (GNU Compiler Collection) installed.
-   Basic knowledge of C programming and Unix commands.

Installation

-   git clone https://github.com/jbettini/Pipex
-   cd Pipex
-   make

Usage

Run the compiled executable with the following syntax :

./pipex file1 cmd1 cmd2 file2

-   file1: Input file.
-   cmd1: First command to execute.
-   cmd2: Second command to execute.
-   file2: Output file.

Exemple :
./pipex infile "ls -l" "grep .c" outfile
