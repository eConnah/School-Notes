Computer processors have different ways of expressing instructions, an instruction set describes the commands an processor can perform. Different types of processors have their own instruction sets but they may perform similar or identical operations. 

# Machine Code
Instructions in machine code are a combination of 1's and 0's, the number of bits used depends on the word length of the processor.

## Operation Code (opcode)
The opcode contains both the actual commands the processor needs to carry out as well as the addressing mode which specifies whether the operand is the actual data, the memory address where the data is held or a register. The addressing mode is usually two bits.

## Operand
This is one or more items of data that are used in the instructions, the type of data is specified by the addressing mode:
- Values: Specified by a 00
- Memory Addresses: Specified by 01
- Registers: Specified by 01