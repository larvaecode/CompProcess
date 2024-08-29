# Compilation Process

## STEP 1: Pre-process

Outputs source code and header files. 
Done with the g++ -E.


## STEP 2: Compiler

Input with the main.i file, outputs assembly file in a *.s file.
Done with g++ -S main.i.

## STEP 3: Assembler

Input with the assembly code file (_.s file). Outputs objet file (_.o).
Done with g++ -c main.s.

## STEP 4: Linker

Input with object file (_.o file). Outputs executable file. 
Done with g++ main.o -o main. 


