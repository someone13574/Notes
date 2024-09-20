[[2. Ohms KVL KCL_F24.pdf]]

---

## Ohm's Law

**Resistance: R**
- The resistance R of an element denotes its ability to resist the flow of electric current.
- The unit of resistance is *ohms* $\ \Omega$
- An element with this property is called a resistor
- Resistors can also be variable

**Ohms' Law**: The voltage across a resistance is directly proportional to the current flowing through it.
# $V = IR$

| ![[Pasted image 20240910143919.png]] | ![[Pasted image 20240910144022.png]] |
| :----------------------------------- | :----------------------------------- |

---
## Examples

1. ![[Lecture 2 - Resistive Circuits 2024-09-10 14.44.06.excalidraw]]
2. ![[Lecture 2 - Resistive Circuits 2024-09-10 14.46.05.excalidraw]]
3. ![[Lecture 2 - Resistive Circuits 2024-09-10 14.49.10.excalidraw]]
### Combining Ohm's Law the Power Formula

- $V=IR$
- $P = VI$

1. $P = I^2R$
2. $P = \frac{V^2}{R}$

![[Lecture 2 - Resistive Circuits 2024-09-10 14.56.52.excalidraw]]

![[Pasted image 20240910150452.png]]

# Concepts and Terms

![[Pasted image 20240910150714.png]]

- Branch $b$ (Number of components)
	- A branch represents a single element such as a voltage source or a resistor.
	- Eg. R4
- Node $n$ (Points of connection)
	- A node is the point of connection between two or more branches
	- Eg. Node 1
- Loop $l$
	- A closed path that never goes twice over a node
		- Eg. The blue line
	- The red path is not a loop
		- It is said to be independent if it contains at least one branch which is not a part of any other loop.

### $l = b - n + 1$
> Where $l$ is the *maximum number of independent* loops.

![[Lecture 2 - Resistive Circuits 2024-09-10 15.10.58.excalidraw]]

# Kirchhoff's Current Law (KCL)

> *The algebraic sum of the currents entering (or leaving) and **node** is zero.
> (The sum of the currents entering a node is equal to the sum of currents leaving the node.)

### $0 = \sum_{n=1}^{N} i_n$

![[Pasted image 20240910151845.png]]

### Examples

![[Lecture 2 - Resistive Circuits 2024-09-10 15.20.38.excalidraw]]
![[Lecture 2 - Resistive Circuits 2024-09-10 15.35.32.excalidraw]]

## Kirchhoff's Voltage Law (KVL)

> *The algebraic sum of the voltages around any loop is zero*

### $0 = \sum_{m=1}^{M} v_m$

- The apply KVL, we must traverse any loop in the circuit and sum to zero the increases and decreases in energy level
	- Plus sign: Decrease in energy level
	- Negative sign: Increase in energy level
- Based on the conservation of energy

![[Lecture 2 - Resistive Circuits 2024-09-10 15.39.30.excalidraw]]

![[Lecture 2 - Resistive Circuits 2024-09-10 15.42.53.excalidraw]]