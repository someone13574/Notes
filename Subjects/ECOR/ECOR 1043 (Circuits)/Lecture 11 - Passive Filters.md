[[Lowpass, Highpass Filters_F24.pdf]]

---

- RC Low-pass filter
	- The transfer function H
		- $V_o = \frac{Z_c}{R + Z_c} \times V_i$ (voltage divider, but with impedance)
		- $H = \frac{V_o}{V_i}=\frac{Z_c}{R + Z_c}$ (transfer function is out/in) 
		- Where
			- $Z_c = \frac{1}{j\omega C} = \frac{1}{j2\pi fC} = \frac{-j}{2\pi fC}$ 
	 - ![[Pasted image 20241010145347.png]]
	 - Magnitude
		 - $H = \frac{X_c}{\sqrt{R^2 + X_c^2}}$ 
		 - Where
			 - $Z_c$ without $j$ 
			 - $X_c = \frac{1}{2\pi fC}$ 
	 - Cut-off frequency
		 - $f_c = \frac{1}{2\pi RC}$ 
	 - Bandwidth
		 - $BW = 0 \text{ Hz to } F_c$  

### Example: RC Low-pass Filter

Find the transfer function $H = V_o / V_i$ of the given RC LPF
![[Pasted image 20241010150835.png]]

$H = \frac{V_o}{V_i} = \frac{Z_c}{R + Z_c}$ 
$R = 5 \Omega$

$Z_c = \frac{1}{j\omega C}$ 
$Z_c = \frac{-j}{\omega (5F)}$ 
$Z_c = \frac{-j}{5 \omega}$ 

$H = \frac{Z_c}{R + Z_c}$
$H = \frac{\frac{-j}{5\omega}}{5 - \frac{j}{5\omega}}$ 

##### Draw Bode Plot using $\omega = 0.2$ 

$H = \frac{1 / 5\omega}{\sqrt{5^2 + (\frac{1}{5\omega})^2}}$ 
$H = \frac{1}{\sqrt{25 + 1^2}}$ 
$H = \frac{1}{5}$ 
$H = 0.2$ 

## $\omega = 1$ 

$H = \frac{1/5}{\sqrt{5^2 + (\frac{1}{5(5)})^2}}$ 
$H = \frac{0.2}{25 + \frac{1}{25}}$ 
$H = 0.04$

## $\omega = 10$ 

$H = 0.004$  

$\text{dB} = 20 \cdot log_{10}(\text{amplitude})$ 

![[Pasted image 20241010151823.png]]

# RC High Pass Filter

- Bandwidth
	- $BW = f_c \text{ to } \infty \text{ (ideally)}$  

## RL Highpass Filter

- Transfer function
	- $V_o = \frac{Z_L}{R + Z_L} \times V_i$ 
	- $H = \frac{V_o}{V_i} = \frac{Z_L}{R + Z_L}$ 
	- $Z_L = j\omega L = j2\pi fL$ 
- Magnitude
	- $H = \frac{X_L}{\sqrt{R^2 + X_L^2}}$ 
	- $X_L = \omega L = 2\pi fL$ 
- Cut-off frequency
	- $f_c = \frac{R}{2\pi L}$  

### Example

![[Pasted image 20241010153638.png]]

$Z_L = j\omega L$
$Z_L = j\omega (500 n) \Omega$ 

$H = \frac{Z_L}{R + Z_L}$ 
$H = \frac{j\omega (500n)}{1 + j\omega (500n)}$ 

$f_c = \frac{R}{2 \pi L}$ 
$f_c = \frac{1 \Omega}{2\pi (500 \times 10^{-9} H)}$ 
$f_c = 318.3 kHz$ 

### Solve at 100 Hz (and $f_c$ and 1 MHz)

$H = \frac{j2\pi f(500n)}{1 + j2\pi f(500n)}$ 
$H = \frac{2\pi f(500n)}{\sqrt{1^2 + (2\pi f 500n)^2}}$ 
$H = \frac{2\pi 100 (500n)}{\sqrt{1^2 + (10000 \pi)^2}}$ 
$H = 0.000314$ 
![[Pasted image 20241010154408.png]]

![[Pasted image 20241010154734.png]]