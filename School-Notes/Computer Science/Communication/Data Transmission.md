Serial data transmission bits are sent one after another along the same data line, this means that only one line is needed to transmit data in one direction. While they are reliable the speed has to suffer as a result. It is more useful for very long distances at very high frequencies. Serial connectors such as usb are much smaller and cheaper than parallel connectors.

Parallel data transmission several bits are sent simultaneously along separate lines or channels. This means that an 8bit block of data will require 8 data channels. As each individual wire has slightly different properties bits travel at slightly different speeds along the wires, this produces a problem known as skew. This refers to electromagnetic interference between two adjacent channels or parallel wires. It gets more pronounced as the frequency of the transmission increases. The transmission can also only be used for distances up to 2m.

In synchronous data transmission all data transfers are timed to coincide with an internal clock pulse, the data is sent as one long stream or block of data with no gaps in the transmission. The receiver then counts the bits and reconstructs the bytes. 
Asynchronous data transmission on the other hand sends each bit separately the moment it is available instead of waiting for a clock signal. Each bytes is preceded by a start bit and ends with a stop bit or stop period a short time gap between each sets of bits. This type of transmission is relatively slow but is a cheap and effective form of serial transmission well suited to low speed connections such as a keyboard and mouse.

Latency is the time delay between the moment the first byte or packet of a communication starts and when it is received at its destination.

All communications between devices require that the devices agree on the format of the data, the set of rules relating to communication devices is called a protocol.

Bit rate is the number of bits transmitted in one second over a wired or wireless connection. Broadband carries multiple signals on a fixed carrier wave, bits are sent as variations on the wave.