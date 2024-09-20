[[3. Single loop circuits_F24.pdf]]

---

# Single-Loop Circuits

- Background
	- Using KVL, KCL, and Ohm's Law, we can write enough equations to analyze any linear circuit.
	- We now start the study of systematic, and efficient, ways of using fundamental circuit laws.
- Single Loop Circuit
	- Elements are in series
	- Elements are in series if they carry the same current
- Goal
	- Start with the simplest one loop, one source circuit
	- Extend the results to multiple source & multiple resistors circuits.

## Voltage Divider: General Equation

- In a single loop circuit with multiple resistors and a voltage source, we can find the voltage across any resistor using Voltage Divider
- According to Voltage Divider, voltage 𝑣𝑅𝑖 across any resistor 𝑅𝑖 is given as:
## $V_{Ri} = \frac{R_i}{R_{eq}}v(t)$
- Where $R_{eq} = R_1 + R_2 + ... + R_N$
- $v(t) =$ Voltage source
- In other words, in single loop circuits, voltage across any resistor is proportional to its value

### Example 1: Find voltage drops across resistors

![[Pasted image 20240912144853.png]]

# Equivalent Resistances: Series

- Summing resistors is the same as analysing them independently
- The current flowing through the circuit sees the same resistance, whether it is a single large resistor or two smaller ones.
- $V = IR$
	- $I = \frac{V_s}{R_1 + R_2}$
- Resistors in series appear as a chain of resistors, they provide only one path for the current to take

# Equivalent Resistance and Sources

- We can also use KVL to find the algebraic sum of voltage sources, or an equivalent voltage source
- ![[Pasted image 20240912151346.png]]
- KVL
	- $V_{R1} + V_2 - V_3 + V_{R2} + V_4 + V_5 - V_1 = 0$
- Collect voltage sources
	- $(-V_1 + V_2 - V_3 + V_4 + V_5) + V_{R1} + V_{R2} = 0$
	- $V_1 - V_2 + V_3 - V_4 - V_5 = V_{R1} + V_{R2}$
	- $V_{eq} = V_{R1} + V_{R2}$
	- $V_{eq}$ = the sum of voltage sources
	- We can now draw an equivalent circuit
	- ![[Pasted image 20240912151739.png]]
- Voltage sources in series add directly
	- Watch out for different polarities
- Resistances also add directly
	- Polarity doesn't matter, they only absorb energy