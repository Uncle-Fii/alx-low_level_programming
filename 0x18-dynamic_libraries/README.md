file libdynamic.so is a C dynamic library containing the function definitions

file main.h is a header file containing the function prototypes

file 1-create_dynamic_lib.sh is a Bash script that creates a dynamic library called liball.so from all the .c files that are in the current directory

file 100-operations.so is a C dynamic library that contains C functions that can be called from Python

file 101-make_me_win.sh is a Bash script to inject the libmask.so library, using LD_PRELOAD, in the giga million program

file libmask.so is a C dynamic library to inject in a giga million program
