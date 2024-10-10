[[8. Source Trans & Super_F24.pdf]]

---

- Thevenin and Norton equivalent circuits represent that same circuit
	- They have the same voltage-current characteristics
- We can equate the two representations, $v=iR_{TH}+V_{OC}$ and $i=\frac{V}{R_{TH}} - i_{sc}$ 
- Solving for $i$ from the Thevenin equivalent
	- $v=iR_{TH}+V_{OC}$
	- $i=\frac{v}{R_{TH}} - \frac{V_{OC}}{R_{TH}}$
- Substituting this $i$ in the Norton equivalent equation
	- $i=\frac{v}{R_{TH}} - i_{sc}$
	- $\frac{v}{R_{TH}} - \frac{V_{OC}}{R_{TH}}=\frac{v}{R_{TH}} - i_{sc}$
	- $v-V_{OC} = v - i_{sc}R_{TH}$
- Solving for $V_{OC}$
	- $V_{OC} = i_{sc}R_{TH}$
- **YOU CANNOT TRANSFORM RESISTORS WHICH YOU ARE MEASURING**