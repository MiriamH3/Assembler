# Assembler
University project - Final C course project.
This project represents an assembler for a custom machine with 4096 bytes and 8 registers. Every byte has 15 bits.
files:
  * assembler.c (Miriam & Racheli) - Contains the main function ,opens and closes input files and if input files are         valid creates output files.
    
  * pre_processor.c (Rachli) - Contains pre processor function witch macros and check macro validation.

  * first_pass.c (Miriam) - Contains functions witch go over input and checks validation according to project's inst.
    and if invalid reports error and moves on to next line. Puts valid info into dedicated Structers.

  * inst_error_check.c (Racheli) - Contains functions that check istruction input.

  * second_pass.c (Miriam & Racheli) - Goes over structers from first pass to check errors of entry and extern lables.

  * header files - Contains declarations of functions and structers in c files.

structers:
  * 
