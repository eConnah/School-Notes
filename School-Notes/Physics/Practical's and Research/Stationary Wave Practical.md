# Background Research:
Stationary waves, also known as standing waves, are formed when two waves of equal frequency and amplitude travel in opposite directions and superpose. The interference of the incident and reflected waves produces a wave pattern that appears stationary at fixed positions along the string. Nodes are the fixed points of zero displacement, while antinodes are the fixed points of maximum displacement. 

## Equations
The equation for the fundamental frequency of a string can be given from:
$$\lambda = 2L$$
$$f = \frac{v}{\lambda}$$
$$f_{1} = \frac{v}{2L}$$
$$v = \sqrt{\frac{F_{t}}{\mu}}$$
$$f_{1} = \frac{1}{2L} \cdot \sqrt{\frac{F_{t}}{\mu}}$$

Where:
- $\lambda$ is wavelength.
- L is the length of the string.
- $f_{1}$ is the fundamental frequency.
- v is wave speed.
- $F_{t}$ is tension.
- $\mu$ is the mass per unit length.

## Hypothesis:
The frequency of the stationary wave will be directly proportional to the square root of the tension in the string.

# Practical
## Equipment: 
- String attached to two points.
- Pulley
- Vibration Generator
- Signal Generator
- Cathode Ray Oscilloscope (CRO)
- Meter Ruler
- Weights

## Diagram:
![[StandingWave.avif]]

## Variables:
Independent - Tension
Dependent - Frequency
Controlled - Length of string, Amplitude, Mass per unit length

## Method:
1. Set up the experiment with a piece of string, a vibration generator, a pulley, slotted masses, a signal generator, a cathode ray oscilloscope (CRO), and a ruler.
2. Choose a tension to start with, and adjust the frequency of the generator until the $2_{nd}$ harmonic appears on the string. This is since the node in the centre is better defined than the antinode's of the $1_{st}$ harmonic.
3. Measure the time period of the wave using the CRO. The time period is the time it takes for one cycle of the wave to pass a point (make only 1 or 2 waves appear for better precision).
4. Calculate the frequency of the wave by taking the reciprocal of double the time period. $f = (2T)^{-1}$
5. Calculate the tension in the string by multiplying the mass of the slotted mass by the acceleration due to gravity. $F_{t} = mg$
6. Repeat steps 1 to 5 for different tensions.
7. Plot $F_{t}$ against $(2Lf)^{2}$ on a graph.
8. Draw a line of best fit through the data points.
9. Calculate the gradient of the line of best fit. The gradient is equal to: $$\frac{F_{t}}{(2Lf)^{2}} = \mu$$ This comes from: $$f = \frac{1}{2L} \cdot \sqrt{\frac{F_{t}}{\mu}}$$ $$f^{2} = \frac{1^{2}}{4L^{2}} \cdot \frac{F_{t}}{\mu}$$ $$\mu = \frac{1}{(2L)^{2}} \cdot \frac{F_{t}}{f^{2}}$$ $$\mu = \frac{F_{t}}{(2Lf)^{2}}$$
10. Measure the actual mass per unit length of the string by placing it on a balance and dividing the mass by the length.
11. Compare the calculated value of $\mu$ with the actual value of $\mu$.
12. Calculating the percentage uncertainty in the time period gives the uncertainty in frequency, and doubling it gives frequency squared.
13. Plot error bars on the graph of $F_{t}$ against $(2Lf)^{2}$.
14. Calculate the percentage uncertainty in the gradient of the line of best fit by doing: $$\frac{\text{Gradient of worst fit - Gradient of best fit}} {\text{Gradient of best fit}} = \text{Uncertainty}$$

## Health and Safety:
- Securely clamp string and generator.
- Ensure no trip hazards.

## Results Table (3.s.f):
| Mass of weights (kg) | Tension (N) | Time Period of $f_{2}$ (s) | Frequency of $f_{1}$ (hz) |
| -------------------- | ----------- | -------------------------- | ------------------------- |
| 0.010                 | 0.0980      | 0.0750                      | 6.66                      |
| 0.020                 | 0.196      | 0.0550                      | 9.09                      |
| 0.030                 | 0.294      | 0.0480                      | 10.4                     |
| 0.040                 | 0.392      | 0.0425                     | 11.8                     |
| 0.050                 | 0.490            | 0.0400                           | 12.5                          |
| 0.060                 | 0.588      | 0.0320                      | 15.6                     |

# Hand-Drawn Graph
A graph plotted with $(2Lf)^{2}$ on the x-axis and $F_{t}$ in newtons on the y-axis using this collected data. The <mark class="hltr-blue">gradient</mark> of this graph gives <mark class="hltr-purple">mass per unit length</mark> ($\mu$) as its value. Based on this graph, we obtained a value of $0.661 \cdot 10^{-3} kgm^{-1}$. This is about $36.7\%$ off the true value of $1.043 \cdot 10^{-3} kgm^{-1}$.

The error bars provided a gradient of worst fit at about $0.734 \cdot 10^{-3} kgm^{-1}$ giving the gradient of the graph an uncertainty of $11.1\%$.

# Evaluation
The discrepancy between our <mark class="hltr-pink">measured result</mark> and the <mark class="hltr-green">true value</mark> can be attributed to these potential sources of error:
- Inaccurate frequency measurements using the oscilloscope 
- Friction in pulley system affecting tension
- Inconsistent tension due to slack/sagging of string
- Possible systematic errors in function generator and oscilloscope

Using electronic timers and sensors could improve frequency and tension measurements. Lubricating the pulley and ensuring a taut string would reduce more uncertainties, and taking many repeat trials and averaging results could reduce random errors.

Overall this experiment yielded an answer close to the true value of $\mu$ but having a difference of $36.7\%$ is quite large. If it is ever to be repeated using more <mark class="hltr-red">precise</mark> equipment that rely less on human measurements could provide a more <mark class="hltr-orange">accurate</mark> answer.

# References:
Research (31-01-24):
- CGP Books (2018). _NEW A-LEVEL PHYSICS FOR 2018 : aqa year 1 & 2 complete revision & practice with._ [online] CGP. Available at: https://www.worldofbooks.com/en-us/books/cgp-books/new-a-level-physics-aqa-year-1-2-complete-revision-practice-with-online-edition/GOR010065392.

Equations (31-01-24):
- www.physicsclassroom.com. (n.d.). _Physics Tutorial: Mathematics of Standing Waves_. [online] Available at: https://www.physicsclassroom.com/class/waves/Lesson-4/Mathematics-of-Standing-Waves.

Diagram 31-01-24:
- Save My Exams. (n.d.). _Required Practical: Investigating Stationary Waves (3.2.4) | AQA A Level Physics Revision Notes 2017_. [online] Available at: https://www.savemyexams.com/a-level/physics/aqa/17/revision-notes/3-waves/3-2-stationary-waves/3-2-4-required-practical-investigating-stationary-waves/.

Method 31-01-24:
- Stationary Wave on String - Required Practical - A-level Physics. (2018). _YouTube_. Available at: https://www.youtube.com/watch?v=aychIrvBBR8.

‌