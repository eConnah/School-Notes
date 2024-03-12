# Theory
This experiment aims to investigate the relationship between the electromotive force (EMF) of a cell, the internal resistance of the cell, and the potential difference delivered to an external circuit. The EMF $(\varepsilon)$, measured in volts $(V)$, represents the ideal voltage a cell can provide. It's the maximum potential difference it can create between its terminals when no current is flowing. The EMF of a cell cannot be directly measured using a voltmeter due to the cell's internal resistance. However, we can estimate it by measuring the open-circuit voltage (OCV), which is the potential difference across the cell's terminals when there is no active current.

Kirchhoff's Second Law states that the sum of the EMFs around a closed loop in a circuit must be equal to the sum of the potential differences across all components. When a current $(I)$ flows through a cell, some energy is lost within the cell due to its internal resistance $(r)$. This results in the potential difference $(V)$ delivered to the external circuit being less than the EMF $(\varepsilon)$. The difference between these two values, $(\varepsilon - V)$, is often referred to as lost volts.

# Equations
To determine the internal resistance and EMF of a cell we can rearrange Kirchhoff's Second Law to plot on a graph:
$$\varepsilon = V + Ir$$
$$V = -rI + \varepsilon$$
$$(y=mx+c)$$
This equation gives us a straight line with $-r$ as the gradient and $\varepsilon$ as the y-intercept.

<div style="page-break-after: always;"></div>

# Practical
## Equipment
- Battery Cell(s)
- Variable Resistor
- Voltmeter
- Ammeter
- Wires

## Diagram
![[Internal Resistance.png]]

## Variables
<mark style="background: #D2B3FFA6;">Independent</mark> Variable: Variable resistor's resistance $(\Omega)$
<mark style="background: #BBFABBA6;">Dependent</mark> Variable: Potential difference across the cell $(V)$ and current $(I)$
<mark style="background: #FF5582A6;">Control</mark> Variables: Cell type, temperature, connecting wires

<div style="page-break-after: always;"></div>

## Safety:
- Use caution when handling electrical circuits.
- Avoid short circuits by ensuring proper connections.
- Dispose of batteries responsibly according to local regulations.
- Make sure there are no exposed <mark style="background: #FF5582A6;">wires</mark>.

## Method
1. Setup the circuit as shown in the above diagram, the internal resistor is implied and not an actual component.
2. Measure the <mark style="background: #BBFABBA6;">voltage</mark> around the cell with the circuit closed to find the EMF.
3. Re-open the circuit.
4. Measure the <mark style="background: #BBFABBA6;">current</mark> and the <mark style="background: #BBFABBA6;">voltage</mark> around the cell and plot in the table.
5. Increase the <mark style="background: #D2B3FFA6;">resistance</mark> of the variable resistor.
6. Repeat steps 4 and 5 for 10 sets of values plotting each set in the table below, try to use a variety of different <mark style="background: #D2B3FFA6;">resistances</mark>.

## Results Table (3.s.f)

|        | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   |
| ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| $I(A)$ | 0.20 | 0.25 | 0.30 | 0.35 | 0.40 | 0.45 | 0.50 | 0.55 | 0.60 | 0.65 |
| $V(V)$ | 1.43 | 1.40 | 1.39 | 1.37 | 1.35 | 1.33 | 1.29 | 1.27 | 1.26 | 1.24 |

<div style="page-break-after: always;"></div>

# Graph
Below is a graph with <mark style="background: #BBFABBA6;">potential difference</mark> $(V)$ on the y-axis against <mark style="background: #BBFABBA6;">current</mark> $(I)$ on the x-axis using our results. The gradient of this graph gives internal resistance of the cell $(R)$ as its value, while the y-intercept gives the EMF of the cell $(\varepsilon)$ as its value. Based on this graph, we obtained a value of $0.430 \Omega$ for resistance and $1.52 V$ for the EMF. The true EMF we recorded at the beginning was $1.47 V$ this gives our experiment a percentage error of $3.40 \%$
![[Internal Resistance.svg]]

<div style="page-break-after: always;"></div>

# Evaluation
While the experiment didn’t have a very large percentage error, it is essential to consider sources of error that may have influenced the result:
- Measurement Errors: Instrument errors in the voltmeter and ammeter could lead to inaccuracies in the recorded values.
- Temperature Variations: Changes in temperature can affect the performance of the cell and its internal resistance.
- Resistance of Connecting Wires: The resistance of the wires connecting the components in the circuit can impact the overall resistance measurement.

Using new and more accurate equipment could potentially increase the accuracy of our result. Plotting more data points may also provide further improvement to both the gradient and y-intercept.
# References
Diagram and Equations 06-03-24:
- M, K. (n.d.). _Required Practical: Investigating EMF & Internal Resistance (5.4.2) | AQA A Level Physics Revision Notes 2017_. [online] Save My Exams. Available at: https://www.savemyexams.com/a-level/physics/aqa/17/revision-notes/5-electricity/5-4-electromotive-force--internal-resistance/5-4-2-required-practical-investigating-emf--internal-resistance/.

Method 06-03-24:
- Malmesbury Education (2018). _EMF & internal resistance - Physics A-level Required Practical_. _YouTube_. Available at: https://www.youtube.com/watch?v=xoxDlu0kswQ.

Graph Software 12-03-24:
- Desmos (2024). _Desmos Graphing Calculator_. [online] Desmos Graphing Calculator. Available at: https://www.desmos.com/calculator.