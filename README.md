# Math-4755-Virus-Dynamics-Project

> Claiming at the beginning that this work was complecated by Max Liu, Jin and Ma. If you wanna contact us, just email me.

> This is the final project for Georgia Tech's math course 4755, Virus Dynamics, Spring in 2019. I have got the permission to push our work here for reference.

### What we've done
Since this is a course project for undergraduates, we simply investigated how a general incidence rate and recovery rate works for an SIR model. By basic ideas and simple methods, we got some consitions for our modified model when its equilibriums are attracting. The model is showing below:

<img src="http://latex.codecogs.com/gif.latex?\\
\begin{equation}
\left\{
\begin{aligned}
\dot{S} &= dN - dS -\dfrac{\beta SI}{\phi(I)}\\
\dot{I} &= \dfrac{\beta SI}{\phi(I)} - dI - r(I)I\\
\dot{R} &= r(I)I -dR
\end{aligned}
\right.
\end{equation}" />
