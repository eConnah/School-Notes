A differential equation is an equation with a function of one or more of its derivatives. For the first order differential equation it comes in the form: $$\frac{dy}{dx}+P(x)y=f(x)$$
 
You first calculate the integrating factor by doing: $$e^{\int{P(x)}d x}$$

Then multiply through by that: $$e^{\int{P(x)}d x} \frac{dy}{dx}+e^{\int{P(x)}d x} P(x)y=e^{\int{P(x)}d x} f(x)$$

You can now simplify the left hand side:
$$\frac{d}{dx}\Bigl (e^{\int{P(x)}d x}y \Bigl )=e^{\int{P(x)}d x} f(x)$$

This works via ![[Product Rule]]
and ![[Chain Rule]]