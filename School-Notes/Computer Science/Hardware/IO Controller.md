# IO Controllers
External devices such as printers, scanners, microphones etc. are produced by different manufacturers. Since they cannot be directly connected to the processor an IO controller acts as the interface between the device and the computer.

# Device Drivers
The software that interacts directly with the IO controller is called a device driver, when you install a new device (e.g. a new printer) you must install the device driver for it (this is usually automatic).

# Tasks
The controller converts the signals received from a peripheral device into a format the computer can process, and vice versa. It receives IO requests from the CPU, and then sends device-specific control signals to the device it is controlling. It also manages the data flow to and from the device, freeing the CPU to get on with other tasks.