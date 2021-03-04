# list.h for userspace
This is the kernel's list.h with some modifications so it works in userspace.
All you need is `list.h` and `list_hacks.h`. This repository also includes some
examples on how to use the list, in case you need them.

To use the list you need to be compiling with the gnu90 standard. You must also
not be using the -pendantic flag for gcc.

# Building the examples
Just `cd` to the examples directory and run `make`. This will create an
executable called `list_examples` in the examples directory.