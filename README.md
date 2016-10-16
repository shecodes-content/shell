# shell

- historically the outer hull of the operating system
- users cannot get to the kernel, they can only get to the shell
- command interpreter
- much like ELIZA, it interprets a line of text after it sees a CR on its input stream of bytes
- it breaks down that text according to a grammar
- the commandline consists of multiple commands that can be combined with logical operators or pipes
- each command consists of a program name and a list of arguments
- arguments can be simple strings/paths, switches/flags or key-value-pairs
- Examples: pwd, cd, ls, cat, less, vim
- environment variables (configuration settings and a way of IPC)
- i/o redirection
- pipes
