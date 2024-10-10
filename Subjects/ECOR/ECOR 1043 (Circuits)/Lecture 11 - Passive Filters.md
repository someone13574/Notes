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