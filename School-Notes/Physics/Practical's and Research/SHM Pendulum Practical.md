The theory states the motion of a pendulum is considered simple harmonic for small angular displacements (less than $15 \degree$), where the restoring force is proportional to the displacement from equilibrium and directed back toward it.

# Equations
$$T = 2 \pi \sqrt{\frac{L}{g}}$$
$$T^{2}=\frac{4\pi^{2}}{g}L$$
$$\log{T}=\frac{1}{2}\log{L}+\log{\frac{2\pi}{\sqrt{g}}}$$

<div style="page-break-after: always;"></div>

# Practical
## Equipment
- Clamp Stand
- Pendulum
- Bob
- Stopwatch
- Metre Ruler
- String

## Diagram
![[SHMPendulum.avif|center|450]]

## Hazards
- The swinging bob can hit objects or people nearby. If the bob is heavy or sharp, this could cause injury. Ensure the pendulum’s path is clear, and stand back during the experiment.
- Sharp edges on the stand or clamp, or mishandling tools while adjusting the pendulum setup, could result in cuts or minor injuries. Handle all equipment with care.

<div style="page-break-after: always;"></div>

## Variables
Independent variable:  <mark style="background: #FF5582A6;">Length</mark> $(L)$
Dependent variable: <mark style="background: #ABF7F7A6;">Time Period</mark> $(T)$
Control variables: Mass $(m)$, No. of <mark style="background: #FFB8EBA6;">oscillations</mark> 

## Method
1. Set up the apparatus, with the <mark style="background: #FF5582A6;">length</mark> of the pendulum at 0.2 m.
2. Make sure the pendulum hangs vertically downwards at equilibrium and inline directly in front of the needle marker.
3. Pull the pendulum to the side at a very small angle then let go. The pendulum will begin to <mark style="background: #FFB8EBA6;">oscillate</mark>.
4. Start the stopwatch when the pendulum passes the needle marker in its equilibrium. One complete <mark style="background: #FFB8EBA6;">oscillation</mark> occurs when the pendulum passes through the equilibrium, to one maximum and then the other, and back to the equilibrium again (not just from side to side).
5. Stop the stopwatch after 10 complete <mark style="background: #FFB8EBA6;">oscillations</mark> and record the total time. Divide the time by 10 to obtain the <mark style="background: #ABF7F7A6;">time period</mark> (which is the mean).
6. Adjust the string to increase the <mark style="background: #FF5582A6;">length</mark> of the pendulum and the wooden block. Repeat the above for 8-10 readings. The ruler is used to measure the string. Ensure it is measured from the wooden blocks to the centre of mass of the bob.

## Results Table

| $l$  | $T_{10 (1)}$ | $T_{10(2)}$ | $T_{10(3)}$ | $T_{10(\text{mean})}$ | $T_{\text{mean}}$ | $T_{u}$    |
| ---- | ------------ | ----------- | ----------- | --------------------- | ----------------- | ---------- |
| 0.20 | 8.80         | 8.68        | 8.67        | 8.72                  | 0.872             | $\pm0.065$ |
| 0.25 | 9.84         | 9.87        | 9.85        | 9.85                  | 0.985             | $\pm0.030$ |
| 0.30 | 10.89        | 10.89       | 10.89       | 10.89                 | 1.089             | $\pm0$     |
| 0.35 | 11.85        | 11.86       | 11.87       | 11.86                 | 1.186             | $\pm0.010$ |
| 0.40 | 12.59        | 12.70       | 12.62       | 12.64                 | 1.264             | $\pm0.055$ |
| 0.45 | 13.47        | 13.48       | 13.50       | 13.48                 | 1.348             | $\pm0.015$ |
| 0.50 | 14.13        | 14.10       | 14.12       | 14.12                 | 1.412             | $\pm0.015$ |

<div style="page-break-after: always;"></div>

## Graph One
### $L$ against $T^{2}$
![[PendulumGraph.svg]]
Using this graph we can get our value of $g$ from calculating the gradient. Here we obtained a value of 3.99 and when put into the formula:
$$g = \frac{4 \pi^{2}}{\text{gradient}}$$
We obtain a <mark style="background: #FFF3A3A6;">measured value</mark> of $9.91ms^{-2}$ for <mark style="background: #D2B3FFA6;">gravity</mark>. This is about $1.0 \%$ off the <mark style="background: #BBFABBA6;">true value</mark> of $9.81 ms^{-2}$.

<div style="page-break-after: always;"></div>

## Graph Two
### $\frac{1}{2} \log{L}$ against $\log{T}$
![[PendulumLogGraph.svg]]
In this graph however, $g$ is calculated from the y-intercept instead of the gradient. We get a value of $0.298$, and when put in the formula:
$$g = \biggl(\frac{2\pi}{10^{\text{intercept}}}\biggl)^{2}$$
We obtain a <mark style="background: #FFF3A3A6;">measured value</mark> of $9.99 ms^{-2}$ for <mark style="background: #D2B3FFA6;">gravity</mark>. This is roughly $1.8 \%$ off the <mark style="background: #BBFABBA6;">true value</mark>.

<div style="page-break-after: always;"></div>

## Evaluation
The discrepancy between the <mark style="background: #BBFABBA6;">true value</mark> and the <mark style="background: #FFF3A3A6;">measured value</mark> for <mark style="background: #D2B3FFA6;">gravity</mark> $(g)$ in the SHM pendulum practical can be attributed to several factors: 
- Slight horizontal swinging of the pendulum bob could have occurred when it was released, affecting the accuracy of time measurements. 
- There may have been errors in measuring the <mark style="background: #FF5582A6;">length</mark> of the pendulum and timing the <mark style="background: #FFB8EBA6;">oscillations</mark>, possibly due to parallax errors or human reaction time when using the stopwatch.
- Air resistance and friction at the pivot point may have introduced damping, altering the natural <mark style="background: #FFB8EBA6;">oscillations</mark>.
- Using larger amplitudes of displacement might have caused the motion to deviate from ideal SHM, where the small-angle approximation no longer holds.
Despite these errors, our measured value of $g$ was $9.91 ms^{-1}$, with only a $1.0 \%$ error from the accepted value, indicating reasonably accurate results. The minor deviation suggests potential systematic errors rather than significant human error .

# References
Method and Diagram (14/10/24):
- Ashika (2017). _Required Practical: Investigating SHM (6.2.8) | AQA A Level Physics Revision Notes 2017_. [online] Save My Exams. Available at: https://www.savemyexams.com/a-level/physics/aqa/17/revision-notes/6-further-mechanics--thermal-physics/6-2-simple-harmonic-motion/6-2-8-required-practical-investigating-shm/.