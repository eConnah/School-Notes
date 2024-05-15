# Fundamental Objective
An experiment to determine the <mark style="background: #FF5582A6;">Resistivity</mark> of a wire by measuring its <mark style="background: #ADCCFFA6;">Resistance</mark> and dimensions.

# Research
The <mark style="background: #FF5582A6;">Resistivity</mark> ($\rho$) of a material is a property that explains its ability to resist the flow of electric <mark style="background: #D2B3FFA6;">Current</mark>. It is determined by the material's characteristics and is a constant at a specific temperature.

# Equations
$$R = \rho LA^{-1}$$
$$\rho = RAL^{-1}$$
Where:
- $R$ is <mark style="background: #ADCCFFA6;">Resistance</mark>, $(\ohm)$
- $\rho$ is <mark style="background: #FF5582A6;">Resistivity</mark>, $(\ohm m)$
- $L$ is length, $(m)$
- $A$ is cross-sectional area, $(m^{2})$

<div style="page-break-after: always;"></div>

# Practical
## Equipment
1. Wire of known material (Constantan)
2. Meter ruler
3. Micrometer
4. Power supply
5. Ammeter
6. Voltmeter
7. Crocodile clips
8. Switch

## Diagram
![[Resistivity.png]]

## Hazards
- Risk of electric shock if proper safety precautions are not followed.
- Accidental short circuits can damage equipment and potentially cause overheating or sparks.
- Be careful when handling wires, crocodile clips, or other sharp instruments.

## Variables
Independent - Length of Wire
Dependent - <mark style="background: #ADCCFFA6;">Resistance</mark>
Controlled - <mark style="background: #FFB86CA6;">Voltage</mark>, Material

<div style="page-break-after: always;"></div>

## Method
1. Setup: Set up the circuit as shown in the diagram, with the wire connected to a power supply, ammeter, and voltmeter. The wire should be straight and taut.
2. Measurement of Length and Diameter: Measure the length (L) of the wire using a meter ruler. Measure the diameter (D) of the wire at several points using a micrometer. Calculate the average diameter.
3. <mark style="background: #ADCCFFA6;">Resistance</mark> Measurement: Connect the circuit to the power supply and set a low <mark style="background: #FFB86CA6;">Voltage</mark>. Record the <mark style="background: #D2B3FFA6;">Current</mark> (I) and <mark style="background: #FFB86CA6;">Voltage</mark> (V) values. Repeat the process for different lengths of wire, ensuring a range of readings.
4. Data Analysis: For each set of values entered in the table, calculate the <mark style="background: #ADCCFFA6;">Resistance</mark> using $R = VI^{-1}$.

## Results Table (3.d.p): 

| Trial | Length (m) | Current (A) | Voltage (V) | Resistance ($\Omega$) |
| ----- | ---------- | ----------- | ----------- | --------------------- |
| 1     | 0.200      | 0.540       | 1.660       | 3.074                 |
| 2     | 0.300      | 0.380       | 1.730       | 4.553                 |
| 3     | 0.400      | 0.450       | 2.690       | 5.978                 |
| 4     | 0.500      | 0.360       | 2.740       | 7.611                 |
| 5     | 0.600      | 0.200       | 1.850       | 9.250                 |
| 6     | 0.700      | 0.170       | 1.860       | 10.941                |
| 7     | 0.800      | 0.230       | 2.810       | 12.217                |

Cross-Section Area ($m^{2}$): $$\pi \cdot (\frac{0.2034}{2000})^{2}$$

<div style="page-break-after: always;"></div>

# Graph
A graph plotted with $L$ in meters on the x-axis and $(R \cdot A)$ in $\ohm m^{2}$ on the y-axis using the data. The gradient of this graph gives <mark style="background: #FF5582A6;">Resistivity</mark> $(\rho)$ as its value. Based on this graph, our <mark style="background: #FFF3A3A6;">measured value</mark> is $4.99 \cdot 10^{-7} ms^{-2}$. This is about $0.248\%$ off the <mark class="hltr-green">true value</mark> of $5.00 \cdot 10^{-7} ms^{-2}$.

![[ResistivityGraph.png]]

<div style="page-break-after: always;"></div>

# Evaluation
The small discrepancy between the <mark class="hltr-green">true value</mark> and our <mark class="hltr-yellow">measured value</mark> could be due to some minor errors in:
- Diameter measurement - using a micrometer has some uncertainty. Taking multiple measurements and averaging reduces this.
- Length measurement - a meter ruler has 1 mm resolution, so length readings are accurate to $\pm1 mm$.
- <mark style="background: #D2B3FFA6;">Current</mark> and <mark style="background: #FFB86CA6;">Voltage</mark> measurements - the ammeter and voltmeter have a certain percentage error. Taking multiple readings helps minimise this.
- <mark style="background: #ADCCFFA6;">Resistance</mark> calculation - using R = V/I means any uncertainty in V and I totals to R. Averaging multiple trials will help improve precision.

However the very small percentage difference of $0.248\%$ between the <mark class="hltr-yellow">measured</mark> and <mark class="hltr-green">true</mark> values indicates that the procedure for measuring <mark style="background: #ADCCFFA6;">Resistance</mark>, dimensions, and plotting the graph was carried out with a high degree of accuracy and precision. The small uncertainty shows excellent technique in taking measurements, controlling variables, and fitting the data.

# References
Diagram and Method (31-01-24):
- Save My Exams. (n.d.). _Required Practical: Investigating Resistivity (5.2.4) | AQA A Level Physics Revision Notes 2017_. [online] Available at: https://www.savemyexams.com/a-level/physics/aqa/17/revision-notes/5-electricity/5-2-resistance--resistivity/5-2-4-required-practical-investigating-resistivity/.

Research and Equations (31-01-24):
- Kelly, D. (2015). _Physics AQA A-level_. London: Collins.