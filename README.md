## Operating Systems Design Course - DIEF UNIMORE ##
## Implementing "head" and "tail" commands in xv6, project by Gasparini Nicolo' ##

The project consist in the implementation of the "head" and "tail" commands in a proper way, so that it may work on the XV6 operating system.
The commands are written using the C language, with the system calls and function available on the basic version of XV6.

The commands both work with multiple options and multiple files, both in number of rows or number of bytes mode, and they work in automatic verbose mode when 2 or more files are specified. It is also possible to not specify the file, thus work with the standard input.

To understand how these commands work it's possible to use the option --help
The possible arguments are:
  -n NUM  to operate with number of lines
  -c NUM  to operate with number of bytes
  -q      quiet mode
  -v      verbose mode
  --version
  --help

2 text files have been added in order to test the function, when removed, the MAKEFILE must be modified too.

NOT IMPLEMENTED:
  multiplier suffix, as in standard unix function
  -NUM option, since it works with -n NUM
