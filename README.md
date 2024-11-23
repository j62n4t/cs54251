java c
EE 113: Digital Signal Processing 
Fall 2024 
Assignment #5 — due Tuesday 11:59 PM, November 19, 2024
1.  (26 points) Let X(Ω) is the DTFT of the signal x[n],recall X(Ω) is periodic with 2π hence, X(Ω+2π) = X(Ω), ∀Ω .  Show that for 0 < βo < 2π, following holds:

This is true for any βo  ∈ R but it is enough to show for 0 < βo < 2π for this exercise. This means for the inverse DTFT, we can start integrating from anywhere as long as we cover 2π .
2.  (24 points) Using the properties of the DTFT such as linearity, time shifting, differentiation property, find the DTFT of the following signals:
(a)  (6 points) x[n] = (0.9)|n| (u[n + 5] + u[n − 5])
(b)  (6 points) x[n] = (0.5)n sin(0.2πn)u[n]
(c)  (6 points) x[n] = cos(πn/5)(u[n] − u[n − 7])
(d)  (6 points) x[n] = n2 (0.5)nu[n]
3.  (25 points) Consider a causal LTI system that is described by the following difference equation:

a)  (6 points) Find the frequency response, H(Ω), plot the |H(Ω)| and ∠(H(Ω)) in MATLAB.
b)  (7 point代 写EE 113: Digital Signal Processing Fall 2024 Assignment #5Matlab
代做程序编程语言s) Find the impulse response sequence, h[n].
c)  (6 points) Write your own MATLAB function, mydiffeq  , to implement this difference equation using a for loop. If the input signal is N-samples long (0 ≤ n ≤ N − 1), your program should find the first N sample of the output y[n] (0 ≤ n ≤ N − 1). Use x[−1] = 0, y[−1] = 0 and y[−2] = 0.
d)  (6 points) Using your Matlab function mydiffeq   , find the first N samples of the impulse response of this system and plot/compare it with the analytical impulse response you found in part b) for N samples.
4.  (25 points) Consider the periodic signal

(a)  (8 points) Find the DTFS representation of this signal. (b)  (9 points) Find the power spectral density, Sx (Ω).
(c)  (8 points) Let N = 20 and L = 5.  Determine what percentage of signal power is preserved if up to 3-rd harmonic (corresponding to k = −3, −2, −1, 0, 1, 2, 3) are kept and the others are discarded. Hint:  You can use MATLAB to  calculate  the  expression.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
