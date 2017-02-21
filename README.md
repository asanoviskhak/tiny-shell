#**Tiny Shell**

###Brief Intro
This is a part of an assignment in my course of System Software. This is a look alike shell program and it has a limited functionality.

###Files
 - Makefile	                - Compiles your shell program and runs the tests
 - README.md	            - This file
 - tsh.c		                    - The heart of this whole project
 - tshref		- The reference shell binary.

----------

###The files that are used to test shell
 - sdriver.pl	# The trace-driven shell driver
 - trace*.txt	# The 15 trace files that control the shell driver
 - tshref.out 	# Example output of the reference shell on all 15 traces

----------

####Little C programs that are called by the trace files
 - myspin.c	- Takes argument <n> and spins for <n> seconds
 - mysplit.c	- Forks a child that spins for <n> seconds
 - mystop.c    - Spins for <n> seconds and sends SIGTSTP to itself
 - myint.c     - Spins for <n> seconds and sends SIGINT to itself


----------


Click [here](https://www.facebook.com/plyterbyrt "Facebook Profile") to know me better.
Drop me a mail at akashgajjar8@gmail.com for any queries or suggestions.
