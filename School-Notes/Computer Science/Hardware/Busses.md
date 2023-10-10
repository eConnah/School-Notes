The control bus is used to send control signals between each [[IO Controller]] and the processor, as well as between the processor and memory, the data bus sends data between CPU components and the address bus sends memory addresses from the processor to CPU components (this bus is one way).

## Signals
- Memory read: Causes data from the addressed location to be placed on the data bus.
- Memory write: Causes data on the data bus to be written into the addressed location.
- Bus request: Indicates that a device is requesting use of the data bus.
- Bus grant: Indicates that the CPU has granted access to the data bus.
- Clock: Used to synchronise operations.

## Words
Memory is divided up in equal units called words, a word's length is usually 8, 16, 32 or 64 bits. Each word also has its own memory address.

# Data Bus
The data bus is bi-directional as data can be sent both ways along the bus, it's width is defined by the number of wires or lines it contains. If the data bus is the same width as a piece of computer data it can be transferred to and from memory in a single operation. If the width is 16 lines and a word is 32 bits, it will require two memory access and data transfer operations. Bus width directly affects overall system performance.