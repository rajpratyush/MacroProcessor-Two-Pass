# MacroProcessor (2 Passes)
## Creating a 2 Pass MacroProcessor using C language as a part of college Coursework.
### This Repo contains all the input and output files for both the passes of the macroprocessor.

## To run it :

### Place macropass1.c, macropass2.c and minp2.txt(input file in the same folder  
### Run macropass1.c 
### Run macropass2.c

## Algorithm for pass 1 of macro processor :-
1) Initialize MNTC ( Macro Name Table ) Counter = 0 and MDTC ( Macro Definition Table

Counter ) = 0

2) Scanning of all macro definitions one by one . If MACRO found in program then for each macro perform:

3) MNTC = MNTC + 1 and enter name of MACRO in MNTC ( Macro Name Table ).

4) For every model statement MDTC = MDTC + 1 in definition of macro

5) Generate argument list array.

## Algorithm for pass 2 of macro processor:-
1) Scan main program for macro call. For each macro call perform.

2) Scan MNT to detect Macro Name and its address in MDT ( Macro Definition Table ).

3) Replacement of all formal parameters by actual parameters.

4) Replace macro call by model statements from MDT.
