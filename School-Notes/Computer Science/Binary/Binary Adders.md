A logic gate circuit can be used to perform the addition of two bits, the two main ones are:
- A Half Adder
- A Full Adder

# Half Adder
A half-adder is a circuit that performs the addition of two bits. It takes an input of two bits A and B and outputs the result S, and the carry C:
- S represents the Sum: $S = A \veebar B$
- C represents the Carry bit: $C = A \land B$
The half-adder has only two inputs so it cannot use the carry from a previous addition as a third input to a subsequent addition. It can only add one-bit numbers.

# Full Adder
A Full Adder combines two Half Adders, it has three inputs A, B and the carry bit C. It's output is still the same.

## Concatenating Full Adders
Multiple full adders can be connected together, n full adders can be connected together to input the carry bit into a subsequent adder along with two new inputs. The concatenated adder can thus add two binary numbers each of n bits.