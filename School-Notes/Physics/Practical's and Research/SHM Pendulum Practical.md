# Equations
$$T = 2 \pi \sqrt{\frac{L}{g}}$$
$$T^{2}=\frac{4\pi^{2}}{g}L$$
$$\log{T}=\frac{1}{2}\log{L}+\log{\frac{2\pi}{\sqrt{g}}}$$


| $l$  | $T_{10 (1)}$ | $T_{10(2)}$ | $T_{10(3)}$ | $T_{10(\text{mean})}$ | $T_{\text{mean}}$ | $T_{u}$    |
| ---- | ------------ | ----------- | ----------- | --------------------- | ----------------- | ---------- |
| 0.20 | 8.80         | 8.68        | 8.67        | 8.72                  | 0.872             | $\pm0.065$ |
| 0.25 | 9.84         | 9.87        | 9.85        | 9.85                  | 0.985             | $\pm0.030$ |
| 0.30 | 10.89        | 10.89       | 10.89       | 10.89                 | 1.089             | $\pm0$     |
| 0.35 | 11.85        | 11.86       | 11.87       | 11.86                 | 1.186             | $\pm0.010$ |
| 0.40 | 12.59        | 12.70       | 12.62       | 12.64                 | 1.264             | $\pm0.055$ |
| 0.45 | 13.47        | 13.48       | 13.50       | 13.48                 | 1.348             | $\pm0.015$ |
| 0.50 | 14.13        | 14.10       | 14.12       | 14.12                 | 1.412             | $\pm0.015$ |

## Graph One
### $L$ against $T^{2}$
![[PendulumGraph.svg]]
Using this graph we can get our value of $g$ from calculating the gradient. Here we obtained a value of 3.99 and when put into the formula:
$$g = \frac{4 \pi^{2}}{\text{gradient}}$$
We obtain a <mark style="background: #FFF3A3A6;">measured value</mark> of $9.91ms^{-2}$ for our <mark style="background: #D2B3FFA6;">spring constant</mark>. This is about $1.0 \%$ off the <mark style="background: #BBFABBA6;">true value</mark> of $9.81 ms^{-2}$.

<div style="page-break-after: always;"></div>

## Graph Two
### $\frac{1}{2} \log{L}$ against $\log{T}$
![[PendulumLogGraph.svg]]
In this graph however, $g$ is calculated from the y-intercept instead of the gradient. We get a value of $0.298$, and when put in the formula:
$$g = \biggl(\frac{2\pi}{10^{\text{intercept}}}\biggl)^{2}$$
We obtain a <mark style="background: #FFF3A3A6;">measured value</mark> of $9.99 ms^{-2}$ for our <mark style="background: #D2B3FFA6;">spring constant</mark>. This is roughly $1.8 \%$ off the <mark style="background: #BBFABBA6;">true value</mark>.