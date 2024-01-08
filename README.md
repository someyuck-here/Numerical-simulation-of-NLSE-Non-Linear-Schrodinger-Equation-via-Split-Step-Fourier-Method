# Numerical-simulation-of-NLSE-Non-Linear-Schrodinger-Equation-by-Split-Step-Fourier-Method

Non-Linear Schrodinger equation is an appromixation for (slow) pulse propagation of light in fibers. It takes into account the dispersion relation (Group Velocity Dispersion-GVD) and the third order nonlinear effect (Self-Phase Modulation-SPM in the most general case). NLSE can be written as -  

$$\frac{\partial A}{\partial z} = - \frac{\iota \beta_2}{2} \frac{\partial^2 A}{\partial \tau ^2} + \iota \gamma |A|^2 A$$ 

It can be observed from the equation that both dispersion and $\chi^{(3)}$ affect only the phase of the pulse. It turns out that dispersion changes the time profile of the pulse (keeping the intensity-frequency profile the same), while SPM changes the frequency profile (keeping the intensity-time profile the same). Thus, the numerical simulation of NLSE exploits this fact by constantly switching between the two domains by utilising modern optimizations to FFT.


