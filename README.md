# simple_shell
# Overview
Sodashy is a sh-compatible command language interpreter that executes commands read from the standard input or from a file.

# Invocation
Usage: Sodash Sodash is started with the standard input connected to the terminal. To start, compile all .c located in this repository by using this command:

gcc -Wall -Werror -Wextra -pedantic *.c -o sodash ./sodash Sodash is allowed to be invoked interactively and non-interactively. If sodash is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

# Authors
James Kamiti
Ivy Thoya

# More information
Sodash is a simple shell unix command interpreter that is part of the alx low level programming module at Alx School and is intended to emulate the basics sh shell. All the information given in this README is based on the sodash and bash man (1) pages.
