Second order differential equations come in the form:
$$a\frac{d^2y}{dx^2}+b\frac{dy}{dx}+cy=f(x)$$
The first step is to solve the auxiliary equation, the constants before the stuff. It forms the quadratic:
$$ax^2+bx+c=0$$
Which will give either one root $\alpha$, two roots $\alpha \beta$ or complex roots $p \pm iq$.
Then the next steps depend on your solutions but here’s the 3 options:
- Two Real Roots - In the case there are two real roots the general solution for the differential equation will be $$y=Ae^{\alpha x}+Be^{\beta x}$$
- One Repeated Root - If the solution is just a single real root then the general solution is $$y=e^{\alpha x}(A+Bx)$$
- Complex Roots - The final case is when the roots or complex in that situation the solution is $$y=e^{px}(A\sin{qx}+B\cos{qx})$$
  
Now that the LHS has been sorted we need to do something with the RHS. Here is a table of the possible things it could be:

| Forms of $f(x)$                      | Forms of P.I.                                 |
| ------------------------------------ | --------------------------------------------- |
| $p$                                  | $\lambda$                                     |
| $p+qx$                               | $\lambda + \mu x$                             |
| $p+qx+rx^2$                          | $\lambda + \mu x + \varphi x^2$               |
| $pe^{kx}$                            | $\lambda e^{kx}$                              |
| $p\cos{\omega x} + q \sin{\omega x}$ | $\lambda \cos{\omega x} + \mu \sin{\omega x}$ |
Once you know the form of the P.I. you need to substitute it back into your differential equation, to do that you will need to differentiate the P.I. twice.

REMEMBER if the auxiliary equation is a repeated root the P.I. needs to be multiplied all by x first.