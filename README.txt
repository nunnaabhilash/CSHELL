This project was done in 3 phases.
1st Phase: Basic linux commands like cd,mkdir,ls etc.
2nd Phase: More commands like piping and redirections.
3rd phase: Handling signals like Cntrl+C,Cntrl+Z etc.

-->This directory contains
		--->main.c ----- It contains main() 
		--->parse.c ---- It contains function for tokenising the input
		--->directory.c- It contains functions for finding present directory shell is working 	
		--->ls.c ------- It contains function for executing all ls -al commands
		--->echo.c ----- It contains function for executing echo command
		--->pinfo.c ---- It contains function for executing pinfo function
		--->redirection.c -- Contains function for redirections
		--->pipe.c ----- It contains function for pipe

-->It contains file os.h in which all libraries are included and all functions are defined.
   We need to include this as #include "os.h" in all modules
--> For executing run make
--> It creates os file 
--> For executing we need to run ./os	
