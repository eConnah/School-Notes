Network cable is commonly called twisted pair, most people use Cat5 or Cat6 cables. The twisting in the cable reduces interference that may cause interference.

# Corruption
## Parity
Parity bits exist to help stop corruption of bits, computers use either odd or even parity. When sending a byte of data, one bit is used as a parity bit, this bit is set to a 1 or 0 to make the total number of odd or even depending on the machine.
Pros:
- Warns the computer when corruption is detected.

Cons:
- If two bits flip then the error wouldn't be caught.

## Majority Voting
Each bit of message is sent three times, the majority would vote for the real bit. So if the bits 0 was sent the machine would actually send 000, the recipient may recieve 001 but since two of the bits are 0 it sets the first bit as 0.
Pros:
- Can fix corruption on its own without asking for the bits to be sent again.

Cons:
- Increases the transmission size.
