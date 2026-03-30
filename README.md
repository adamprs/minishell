# minishell

## Description

minishell is a project that consists of creating a simple UNIX shell, inspired by Bash.

The program provides an interactive prompt where users can execute commands, manage processes, and interact with the system environment. It handles command parsing, execution, pipes, redirections, and environment variable expansion.

This project focuses on process management, file descriptors, parsing, and signal handling, offering a deep understanding of how shells work internally.

## Instructions

### Compilation
```bash
make
Execution
./minishell
The shell will display a prompt and wait for user input.
Features

Display a prompt and handle command history
Execute commands using PATH, absolute or relative paths
Handle quotes:
' prevents interpretation of metacharacters
" allows $ expansion


Environment variables expansion ($VAR, $?)
Redirections:
< input
> output
>> append
<< heredoc


Pipes (|) between commands
Signal handling:
Ctrl-C, Ctrl-D, Ctrl-\


Built-in commands:
echo -n
cd
pwd
export
unset
env
exit



Bonus

Logical operators:
&& (AND)
|| (OR)
Parentheses for priority


Wildcards:
* expansion in current directory



Resources

Bash manual
POSIX documentation
man pages (fork, execve, pipe, dup2, etc.)
GNU Readline documentation
