Each time the subroutine is called, the return address, parameter and local variables are pushed onto the stack. A recursive routine has three essential characteristics:
- A stopping condition or base case must be included which when met means that the routine will not call itself and will start to "unwind".
- For input values other than the stopping condition, the routine must call itself.
- The stopping condition must be reached after a finite number of calls.
Every time a subroutine is called, the return address (the line after CALL statement) is put on the call stack. Even with a stopping condition, the recursive routine can only be called a limited number of times or the stack will overflow the maximum memory capacity.