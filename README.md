# MiniShell
MiniShell is a simplified version of a command-line shell (like Bash or Zsh). It allows users to execute commands, manage processes, and interact with the operating system through a text-based interface. This project demonstrates how shells work internally and helps in learning system calls, process management, and string parsing in C.
Features

Accept and execute basic shell commands.

Handle internal commands like:

cd (change directory)

pwd (print working directory)

exit (quit shell)

Execute external programs (e.g., ls, cat, echo).

Support for input/output redirection (>, <).

Support for pipes (|) between commands.

Error handling for invalid commands.

Example Workflow

User starts the MiniShell.

Prompt (myshell>) appears.

User enters a command → MiniShell parses it → executes using system calls.
myshell> pwd
/home/user/projects

myshell> ls -l
-rw-r--r--  1 user user   512 Sep 28  main.c
-rw-r--r--  1 user user  1024 Sep 28  minishell.c

myshell> echo Hello World
Hello World

myshell> exit
Goodbye!
Use Cases

Learn how a shell works internally.

Practice with fork(), exec(), wait(), chdir() system calls in Linux.

Strong project for OS & Systems Programming learning.

Base project for implementing advanced shells.

Example Output:
