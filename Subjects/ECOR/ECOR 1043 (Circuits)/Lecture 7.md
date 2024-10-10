[[7. Thevenin_Norton_F24.pdf]]

---

- Special Cases of Resistance
	- Variable resistor
		- Resistor with line through it
	- Short-Circuit
		- Zero resistance, connected by water
	- Open-Circuit
		- No connection, infinite resistance
- Thévenin and Norton's Theorems
	- Replace a complicated circuit with a simple one
	- Make analysis easier when performing & evaluating load design
	- We replace circuit "A" with a simple circuit with the same voltage-current characteristics.
- Thévenin theorem
	- Replaces the linear two-terminal circuit with a voltage source in series with a resistance
	- $V_{OC}$ is the terminal voltage if $i == 0$ (open-circuit voltage)
	- Thévenin voltage $V_{TH} = V_{OC}$
	- $R_{TH}$ is the equivalent resistance seen at the terminals (the Thévenin resistance).
- Procedure to get the Thévenin equivalent
	1. Identify and isolate the circuit and terminals for which the Thévenin equivalent circuit is desired.
	2. Eliminate the independent sources in the circuit and determine the equivalent resistance for the circuit.
		- Remove paths with current source
		- Replace voltage sources with wires
	3. Re-activate the sources and determine the open-circuit voltage across the circuit terminals.
		- Can use nodal or loop analysis
		- Remember that voltage through a resistor is the same if no other paths are possible.
	4. Place the Thévenin equivalent circui into the original overall circuit and perform the desired analysis.
- Norton Theorem
	- Any linear two-terminal circuit can also be modelled as a current source in parallel with a resistor
	- $I_{SC}$ is the short-circuit current through the terminals
- Norton Theorem Procedure
	1. Identify and isolate the circuit and terminals in the circuit for which the Norton equivalent circuit is desired
	2. Eliminate sources and determine $R_{TH}$ of the circuit
	3. Re-activate the sources, short-circuit the output terminaks and determine $I_{SC}$.
	4. Place the Norton eqivalent circuit into the original overall circuit and perform the desired analysis.
- 