# get_next_line
get_next_line is a project assigned by the school 42 that aims to teach students how to use file descriptors, buffer reading, and static variables.

## Overview
The goal of this project is to write a function that reads a single line from a file descriptor, without knowing its size beforehand, and saves the result in a statically allocated buffer.

The function int get_next_line(int fd, char **line) takes two arguments:

int fd: the file descriptor to read from.
char **line: a pointer to a pointer to a character, where the read line will be saved.
The function should return 1 when a line has been read, 0 when the reading has been completed, and -1 if an error occurs.

## Compilation
To compile the project, run the following command in the root directory of the project:

make

This will compile the libft library and the get_next_line function.
