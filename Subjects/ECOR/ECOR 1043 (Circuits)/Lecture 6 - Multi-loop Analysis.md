[[6. Multi-loop_circuits_F24.pdf]]

---

- Multi-loop circuits have more complex analysis than basic one loop circuits
- We introduce a new type of analysis
- Multi-Loop Analysis: Mesh Analysis
	- This method uses the "Loop" equations of Kirchoff's Voltage Law as well as Ohm's Law to find the various currents around the circuit.
- When a voltage source is connected to two non-reference (ground) nodes, nodal analysis is more involved.
- When a current source is shared by two meshes, mesh analysis is more involved
- Use $l = b - n + 1$ to get the number of independent loops


- Definitions
	- Loop: A closed path that does not go over any node twice
	- Mesh: A loop that does not enclose any other loop
	- Loop Current: A fictitious current that is assumed to flow around a loop.
	- Mesh current: A loop current associated with a mesh
	- We can calculate currents through various components by using loop currents

- Mesh analysis steps
	0. Determine how many meshes/loops we need
	1. Identify all meshes's and assign mesh currents
	2. For each loop with an unknown current, write a KVL equation (SKIP)
	3. Replace voltages in terms of mesh currents (SKIP)
	4. Solve for mesh currents
	5. Solve for unknown currents as needed
	6. Use currents to solve for voltages

Shortcut:

Skip directly to $R_{eq}I_N + \text{shared loops' branches} + V = 0$