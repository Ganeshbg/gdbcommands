# gdbcommands


gcc -g program.c

gdb ./a.out

To set breakpoints:
-------------------

(gdb) break linenumber

To on disable randomization:
----------------------------

Sometimes the program works well inside gdb, but gives segfault when run normally
To detect where the segfault is happenning

(gdb)set disable-randomization off

To run the program in gdb:
--------------------------

(gdb)run or r

To continue execution after breakpoint:
---------------------------------------

(gdb)continue

To do line by line:
-------------------

Run the program using "run" or "r". If you need any break points on a particular line, put break points and then run. Then use "next" to do line by line execution.

(gdb)next

To print certain variable values while running:
-----------------------------------------------

(gdb)print variable_name


To quit:
--------
(gdb)q
