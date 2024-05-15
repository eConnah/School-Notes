# Fundamental Objective
This experiment aims to investigate the relationship between the electromotive force (<mark style="background: #FF5582A6;">EMF</mark>) of a cell, the internal resistance of the cell, and the potential difference delivered to an external circuit.

# Research
The <mark style="background: #FF5582A6;">EMF</mark> $(\varepsilon)$, measured in volts $(V)$, represents the ideal <mark style="background: #FFB86CA6;">Voltage</mark> a cell can provide. It's the maximum potential difference it can create between its terminals when no <mark style="background: #D2B3FFA6;">Current</mark> is flowing. The <mark style="background: #FF5582A6;">EMF</mark> of a cell cannot be directly measured using a voltmeter due to the cell's internal resistance. However, it can be estimated by measuring the open-circuit <mark style="background: #FFB86CA6;">Voltage</mark> (OCV), which is the potential difference across the cell's terminals when there is no active <mark style="background: #D2B3FFA6;">Current</mark>.

Kirchhoff's Second Law states that the sum of the <mark style="background: #FF5582A6;">EMF</mark>s around a closed loop in a circuit must be equal to the sum of the potential differences across all components. When a <mark style="background: #D2B3FFA6;">Current</mark> $(I)$ flows through a cell, some energy is lost within the cell due to its internal resistance $(r)$. This results in the potential difference $(V)$ delivered to the external circuit being less than the <mark style="background: #FF5582A6;">EMF</mark> $(\varepsilon)$. The difference between these two values, $(\varepsilon - V)$, is often referred to as lost volts.

# Equations
$$\varepsilon = V + Ir$$
$$V = -rI + \varepsilon$$
$$(y=mx+c)$$
Where:
- $\varepsilon$ is <mark style="background: #FF5582A6;">EMF</mark>, $(V)$
- $V$ is <mark style="background: #FFB86CA6;">Voltage</mark>, $(V)$
- $I$ is <mark style="background: #D2B3FFA6;">Current</mark>, $(I)$
- $r$ is Internal <mark style="background: #ADCCFFA6;">Resistance</mark>, $(\ohm)$

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
Independent Variable: Variable resistor's <mark style="background: #ADCCFFA6;">Resistance</mark> $(\Omega)$
Dependent Variable: Potential difference across the cell $(V)$ and <mark style="background: #D2B3FFA6;">Current</mark> $(I)$
Control Variables: Cell type, temperature, connecting wires

<div style="page-break-after: always;"></div>

## Safety:
- Use caution when handling electrical circuits.
- Avoid short circuits by ensuring proper connections.
- Dispose of batteries responsibly according to local regulations.
- Make sure there are no exposed wires.

## Method
1. Setup the circuit as shown in the above diagram, the internal resistor is implied and not an actual component.
2. Measure the <mark style="background: #FFB86CA6;">Voltage</mark> around the cell with the circuit closed to find the <mark style="background: #FF5582A6;">EMF</mark>.
3. Re-open the circuit.
4. Measure the <mark style="background: #D2B3FFA6;">Current</mark> and the <mark style="background: #FFB86CA6;">Voltage</mark> around the cell and plot in the table.
5. Increase the resistance of the variable resistor.
6. Repeat steps 4 and 5 for 10 sets of values plotting each set in the table below, using a different <mark style="background: #ADCCFFA6;">Resistance</mark> each time.

## Results Table (3.s.f)

|        | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   |
| ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| $I(A)$ | 0.20 | 0.25 | 0.30 | 0.35 | 0.40 | 0.45 | 0.50 | 0.55 | 0.60 | 0.65 |
| $V(V)$ | 1.43 | 1.40 | 1.39 | 1.37 | 1.35 | 1.33 | 1.29 | 1.27 | 1.26 | 1.24 |

<div style="page-break-after: always;"></div>

# Graph
Below is a graph with potential difference $(V)$ on the y-axis against <mark style="background: #D2B3FFA6;">Current</mark> $(I)$ on the x-axis using our results. The gradient of this graph gives internal <mark style="background: #ADCCFFA6;">Resistance</mark> of the cell $(R)$ as its value, while the y-intercept gives the <mark style="background: #FF5582A6;">EMF</mark> of the cell $(\varepsilon)$ as its value. Based on this graph, our <mark style="background: #FFF3A3A6;">measured value</mark> was $0.430 \Omega$ for <mark style="background: #ADCCFFA6;">Resistance</mark> and $1.52 V$ for the <mark style="background: #FF5582A6;">EMF</mark>. The <mark style="background: #BBFABBA6;">true value</mark> we recorded at the beginning was $1.47 V$ this gives our experiment a percentage error of $3.40 \%$
![[Internal Resistance.svg]]

<div style="page-break-after: always;"></div>

# Evaluation
While the experiment didn’t have a very large percentage error, it is essential to consider sources of error that may have influenced the result:
- Measurement Errors: Instrument errors in the voltmeter and ammeter could lead to inaccuracies in the recorded values.
- Temperature Variations: Changes in temperature can affect the performance of the cell and its internal <mark style="background: #ADCCFFA6;">Resistance</mark>.
- <mark style="background: #ADCCFFA6;">Resistance</mark> of Connecting Wires: The <mark style="background: #ADCCFFA6;">Resistance</mark> of the wires connecting the components in the circuit can impact the overall <mark style="background: #ADCCFFA6;">Resistance</mark> measurement.

Using new and more accurate equipment could potentially increase the accuracy of our result. Plotting more data points may also provide further improvement to both the gradient and y-intercept.
# References
Diagram and Equations 06-03-24:
- M, K. (n.d.). _Required Practical: Investigating EMF & Internal Resistance (5.4.2) | AQA A Level Physics Revision Notes 2017_. [online] Save My Exams. Available at: https://www.savemyexams.com/a-level/physics/aqa/17/revision-notes/5-electricity/5-4-electromotive-force--internal-resistance/5-4-2-required-practical-investigating-emf--internal-resistance/.

Method 06-03-24:
- Malmesbury Education (2018). _EMF & internal resistance - Physics A-level Required Practical_. _YouTube_. Available at: https://www.youtube.com/watch?v=xoxDlu0kswQ.

Graph Software 12-03-24:
- Desmos (2024). _Desmos Graphing Calculator_. [online] Desmos Graphing Calculator. Available at: https://www.desmos.com/calculator.