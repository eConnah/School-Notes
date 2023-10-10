Early computers were able to calculate an output using fixed instructions but they could perform only that one set of instructions. A general purpose computer can perform many different tasks at different times. Their programming is not fixed. To achieve this, computers are designed to allow data and instructions to be stored — this is called the stored program concept. Machine code instructions are loaded into main memory to be executed by the processor, the instructions are fetched one at a time and executed immediately by the processor in a sequential order. 

# von Neumann Architecture
The most common implementation of this concept is the von Neumann architecture. Instructions and data are stored in a common main memory and transferred using a single shared bus.

# Harvard Architecture
An alternative model separates the data and instructions into separate memories using different buses. Program instructions and data are no longer competing for the same bus. This is most commonly used in embedded systems where speed is a priority.

# Comparison
Owing primarily to cost and programming complexity, almost all general purpose computers are based on von Neumann's principles. Harvard principles are usually used with specialist embedded systems such as digital signal processing where speed takes priority over the complexities of design.