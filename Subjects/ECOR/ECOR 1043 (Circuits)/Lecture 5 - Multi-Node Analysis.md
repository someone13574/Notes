[[5. Multi-node_circuits_F24.pdf]]

---

- Multi-Node circuits are circuits with more than two nodes.
	- Analysis is more complex
	- We introduce a new type of analysis
- Nodal Analysys
	- Uses the nodal equations
		- Kirchhoff's Current Law
		- Ohm's Law
		- Finds the voltages

- Set a reference node (ground)
	- Voltages are meaningless without a reference
	- We assume the reference is ground to give it meaning
	- Any node voltage is measured in reference to ground unless otherwise defined.
- Steps
	- Identify all nodes and select a reference node
	- Identify all known node voltages
	- At eahc node with an unknown voltage, write a KCL equation
	- Replace currents in terms of node voltages
	- Solve for the unknown voltages as needed
	- Use voltages to solve for any desired values.