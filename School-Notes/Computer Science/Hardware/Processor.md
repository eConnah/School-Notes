# Arithmetic Logic Unit
The ALU is the problem solving part of the processor, this component performs arithmetic, logical and shift operations on data:
- Arithmetic operations: Add, Subtract, Multiply and Divide
- Logical operations: AND, OR, NOT, XOR
- Shift operations: Move bits to the left or right within a register

# Control Unit
The part of the processor that coordinates the activity of all other components Each instruction is accepted and decoded Separate steps such as fetching the  address of data, and fetching the data itself from memory, are identified Each step is synchronised with a regular pulse from the system clock.

# System Clock
The system clock is a series of regular ON/OFF signals that are used to synchronise the operations of the processors components. Actions are usually carried out on the rising edge of the clock, and each action takes a fixed number of cycles to complete.

# General Purpose Registers
Results from the ALU need to be stored somewhere, rather than writing working data back to 'slow' memory, processors have several locations of super-fast memory called registers that are used to temporarily store results. The processor is then able to immediately access and re-use these results in subsequent calculations, some processors only have a single general purpose register called an Accumulator.

# Registers
- Program Counter (PC): The Program Counter keeps track of the memory address of the next instruction to be fetched and executed.
- Instruction Register (IR): The Instruction Register holds the currently fetched instruction being executed.
- Status Register (SR): The Status Register contains individual bits that indicate the outcome of operations, such as carry, overflow, zero result, and others.
- Memory Address Registers (MAR): Address Registers store memory addresses for data access or for transferring data between different memory locations.
- Data Registers (DR): These registers store data fetched from memory or obtained from input/output operations.
- Memory Buffer Register (MBR): The register in a computer's CPU that stores the data being transferred to and from the immediate access storage.

# Executing Instructions
Carrying out sequences of programming instructions requires many different snippets of information to be held. The processor has to temporarily hold the current instruction being executed, the address of the data that it needs, and also the data itself. It has to keep track of the address of the next instruction to be executed.

# Fetch-Execute Cycle
Processors operate in defined stages that are used to carry out program instructions The process is repeated over and over again for each instruction in a program. The Fetch-Execute cycle is triggered from the clock pulses of the system clock. The faster the clock speed, the faster a computer can fetch, decode and execute instructions

The **fetch-execute cycle**, also known as the **instruction cycle**, is the fundamental process by which a computer's central processing unit (CPU) operates to execute instructions. Here’s a breakdown of the steps:

## Fetch
   Step 1: PC (Program Counter) Points to Next Instruction
     The Program Counter holds the memory address of the next instruction to be executed.
   Step 2: Instruction is Retrieved from Memory
     The CPU fetches the instruction stored at the memory address pointed to by the Program Counter.
   Step 3: Update the Program Counter
     After fetching the instruction, the Program Counter is updated to point to the next instruction, typically incrementing to the next address in memory.
   
## Decode
   Step 1: Instruction Decoding
     The fetched instruction is sent to the instruction decoder, where the CPU determines what the instruction is and what it needs to do.
   Step 2: Identify Operands
     The instruction may contain references to data or operands that are stored in registers or memory, which need to be accessed.

## Execute
   Step 1: Perform the Operation
     The CPU carries out the decoded instruction. This could involve performing an arithmetic operation (e.g., addition), a logical operation (e.g., comparison), moving data between registers, or interacting with input/output devices.
   
## Store (or Write Back)
   Step 1: Store Result (if necessary)
     The result of the executed instruction is written back to a specific register or memory location, if required.

## Repeat
   After storing the result, the cycle starts again with the next instruction being fetched from the location specified by the updated Program Counter.

The process repeats continuously while the CPU is operating, allowing it to execute programs.

# Cache Memory
Cache is a small amount of superfast memory that stores data that is frequently used by the processor. It's larger but slower than a register, and faster but smaller than RAM. Larger amounts of cache memory can improve processing speed.

# Interrupts
An interrupt is a signal by a software program or a hardware device sent to the CPU. A software interrupt occurs when an application program terminates or requests certain services from the operating system. A hardware interrupt occurs when an IO operation is complete or an error such as "Printer out of paper" occurs. A test for interrupts is made at the end of each instruction cycle. Execution is suspended and the contents of all registers are temporarily saved the interrupt service routine is then called to deal with the interrupt.