Write a script that prints the absolute path name of the current working directory.
Up until now, we have seen a number of commands and their mysterious options and arguments. In this lesson, we will try to remove some of that mystery. We will introduce the following commands.

type - Display information about command type
which - Locate a command
help - Display reference page for shell builtin
man - Display an on-line command reference
Commands can be one of 4 different kinds:

An executable program like all those files we saw in /usr/bin. Within this category, programs can be compiled binaries such as programs written in C and C++, or programs written in scripting languages such as the shell, Perl, Python, Ruby, etc.
A command built into the shell itself. bash provides a number of commands internally called shell builtins. The cd command, for example, is a shell builtin.
A shell function. These are miniature shell scripts incorporated into the environment. We will cover configuring the environment and writing shell functions in later lessons, but for now, just be aware that they exist.
An alias. Commands that we can define ourselves, built from other commands. This will be covered in a later lesson.
