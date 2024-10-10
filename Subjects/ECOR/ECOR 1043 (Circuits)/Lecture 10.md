[[FrequencyResponse_F24.pdf]]

---

- Any signal can be written in the time domain or frequency domain
- Frequency response
	- The variation in a circuit's behaviour with change in signal frequency
- Transfer function H($\omega$)
	- A frequency dependents ratio of output (response) to the input (source) of a circuit. $H(\omega) = \frac{Y(\omega)}{X(\omega)}$
	- Typically given as a ratio of voltages for our applications, comparing output voltage to input voltage
		$H(\omega) = \frac{V_o(\omega)}{V_s(\omega)}$
		$H = \frac{V_o}{V_s} = \frac{1}{\omega^3}$ 
	Decibal
		For far we've calculated in Volts and compared them wha
		Once we have our values in dB, we can plot our transfer function. This is called a Bode plot.
	- Amplitude 
### $|dB|=20log_{10}(\frac{V_o}{V_s})$

- Filters
	- Low-pass
		- Low frequency signals stay
	- High-pass
		- High freq stays
	- Bandpass
		- Medium freqs stay
		- Makes a hill or "band" shape
	- Notch filter
		- High and low freqs stay. Makes a notch or divot shape.
	- Ideals are sharp cutoffs. Realistic responses are smoothed out.
	- Passband
		- Range of frequencies that are allowed to pass through the filter with the minimum attenduation (usually defined as less than -3 dB (70.7%) of attenuation)
	- Stopband
		- Opposite of passband
	- Bandwidth (BW): width of the passband
	- Roll-off
		- Rate a which attenuation increases/decreases after/before the cut-off frequency