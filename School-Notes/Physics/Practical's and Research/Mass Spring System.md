The theory behind the <mark style="background: #FF5582A6;">mass</mark>-spring system is based on Hooke's Law and Newton's Second Law of Motion. Hooke's Law states that the force exerted by a spring is directly proportional to the <mark style="background: #CACFD9A6;">displacement</mark> from its equilibrium position.

## Equations
$$T = 2 \pi \sqrt{\frac{m}{k}}$$
$$T^{2}=\frac{4\pi^{2}}{k}m$$
$$\log{T}=\frac{1}{2}\log{m}+\log{\frac{2\pi}{\sqrt{k}}}$$
Where:
- $T$ is <mark style="background: #ABF7F7A6;">Time Period</mark>, measured in $s$.
- $m$ is <mark style="background: #FF5582A6;">mass</mark>, measured in $kg$.
- $k$ is <mark style="background: #D2B3FFA6;">spring constant</mark>, measured in $Nm^{-1}$

<div style="page-break-after: always;"></div>

# Practical
## Equipment
- Clamp Stand
- Spring
- Masses
- Stopwatch
- Metre Ruler
- Pendulum

## Diagram
![[MassSpringSystem.avif|center|450]]

## Hazards
- Be careful not to snap the spring as it may spring back and cut you.
- Wear safety goggles to protect eyes from springs and masses.

<div style="page-break-after: always;"></div>

## Variables
Independent variable = <mark style="background: #FF5582A6;">Mass</mark> $(m)$
Dependent variable = <mark style="background: #ABF7F7A6;">Time Period</mark> $(T)$
Control variables:
- <mark style="background: #D2B3FFA6;">spring constant</mark> $(k)$
- Number of Oscillations

## Method
1. Set up the apparatus, with no masses hanging on the holder to begin with (just the 100 g <mark style="background: #FF5582A6;">mass</mark> attached to it)
2. Pull the <mark style="background: #FF5582A6;">mass</mark> hanger vertically downwards between 2-5 cm as measured from the ruler and let go. The <mark style="background: #FF5582A6;">mass</mark> hanger will begin to oscillate
3. Start the stopwatch when it passes the nail marker
4. Stop the stopwatch after 10 complete oscillations and record this time. Divide the time by 10 for the <mark style="background: #ABF7F7A6;">Time Period</mark> (which is the mean)
5. Add a 50 g <mark style="background: #FF5582A6;">mass</mark> to the holder and repeat the above between 8-10 readings. Make sure the <mark style="background: #FF5582A6;">mass</mark> is pulled down by the same length before letting go

## Results Table

| Mass $kg$ | $T_{10}$ | $T_m$ |
| --------- | -------- | ----- |
| 0.05      | 2.96     | 0.296 |
| 0.10      | 4.10     | 0.410 |
| 0.15      | 5.20     | 0.520 |
| 0.20      | 5.91     | 0.591 |
| 0.25      | 6.62     | 0.662 |
| 0.30      | 7.16     | 0.716 |
| 0.35      | 7.74     | 0.774 |

<div style="page-break-after: always;"></div>

## Graph One
### $m$ against $T^{2}$
![[MassSpringSystem.svg]]
Using this graph we can get our value of $k$ from calculating the gradient. Here we obtained a value of 1.73 and when put into the formula:
$$k = \frac{4 \pi^{2}}{\text{gradient}}$$
We obtain a <mark style="background: #FFF3A3A6;">measured value</mark> of $22.9Nm^{-1}$ for our <mark style="background: #D2B3FFA6;">spring constant</mark>. This is about $11.9 \%$ off the <mark style="background: #BBFABBA6;">true value</mark> of $26 Nm^{-1}$.

<div style="page-break-after: always;"></div>

## Graph Two
### $\frac{1}{2} \log{m}$ against $\log{T}$
![[MassSpringSystemLog.svg]]
In this graph however, $k$ is calculated from the y-intercept instead of the gradient. We get a value of $0.120$, and when put in the formula:
$$k = \biggl(\frac{2\pi}{10^{\text{intercept}}}\biggl)^{2}$$
We obtain a <mark style="background: #FFF3A3A6;">measured value</mark> of $22.7 Nm^{-1}$ for our <mark style="background: #D2B3FFA6;">spring constant</mark>. This is roughly $12.5 \%$ off the <mark style="background: #BBFABBA6;">true value</mark>.

<div style="page-break-after: always;"></div>

## Evaluation
The discrepancy between the true value and the measured value for the <mark style="background: #D2B3FFA6;">spring constant</mark> can be attributed to these factors:
- Noticed slight swinging when letting go of the <mark style="background: #FF5582A6;">mass</mark>.
- Inaccurate <mark style="background: #FF5582A6;">mass</mark>, <mark style="background: #CACFD9A6;">displacement</mark>, or time measurements (due to parallax error, reaction time, etc.).
- Friction and damping (air resistance, internal friction in the spring).
- Non-ideal spring behaviour (non-linear response or deformation beyond the elastic limit).
- Oscillation amplitude (large amplitudes causing non-linear effects).
With our percentage error being around $12 \%$ it indicates room for improvement but the results weren’t bad with our coefficient of determination being $0.999$. This implies our results were extremely precise and the error could be a constant systematic error instead of a human error.

## References
Method and Diagram (03/10/24):
- Ashika (2017). _Required Practical: Investigating SHM (6.2.8) | AQA A Level Physics Revision Notes 2017_. [online] Save My Exams. Available at: https://www.savemyexams.com/a-level/physics/aqa/17/revision-notes/6-further-mechanics--thermal-physics/6-2-simple-harmonic-motion/6-2-8-required-practical-investigating-shm/.

‌