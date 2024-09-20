
Notes: [[1. Intro & Basic Concepts_F24.pdf]]

---

**Electric circuit**
- An interconnection of electrical components that allow electrons to flow and perform a useful function.
- It can be described with a mathematical model to predict its behaviour.

### Basic quantities

**SI Unit Prefixes**
- pico (p) = $10^{-12}$
- nano (n) = $10^{-9}$
- micro ($\micro$) = $10^{-6}$
- milli (m) = $10^{-3}$
- 1
- kilo (k) = $10^3$
- mega (M) = $10^6$
- giga (G) = $10^9$
- tera (T) = $10^{12}$

**Electric Charge (q)**
- Charge is an electrical property of the atomic particles
- Measured in *coulombs (C)*.
	- 1 coulomb = $6.241 \times 10^{18} \text{ e}$
- Similar to an amount of water

**Electric Current (i)**
- The time rate of change of charge (or flow of charge over time)
- The basic unit of current is the *ampere (A)*
- Similar to water flowing

**Voltage (electromotive force, potential, or potential difference v)**
- The difference in energy level required to move a unit charge between two points.
- A push or pressure to move electrons resulting in current
- Basic unit is a volt (V)
- Voltage is always measured in a relative form as the difference between two points.
- Similar to water pressure

**Power (p)**
- Time rate of change of energy (delivered or absorbed)
- Measured in Walls (W)
- Related to current and voltage through the equation $p = v \times i$
- Water example: High pressure and large amount of water have more power.

### Circuit elements

Devices that are completely characterised by the current through the element and/or the voltage across it.

- Active: Generate power
	- Voltage sources
		- Has positive and negative terminal
		- Has a set voltage across it
	- Current sources
- Passive: Absorb/dissipate power
	- Resistors!
	- Capacitors
	- Inductors

*Conventional Current* assumes that current flows out of the positive terminal, through the circuit and into the negative terminal of the source.

**Passive Sign Convention (PSC)**
- **Voltage is measured with the side which the current enters as positive**
	- If this is not followed, the sign will be wrong.
- We need to establish the sign of the current relative to the voltage for passive circuit elements.
- Assumes that current enters the node at the higher voltage (the positive side)
- Sign is known for active circuit elements, with convention only applies for passive elements
- If both voltage polarity and current direction are both not given, we can arbitrarily assume one of them.
	- Once we assume one, the other is dictated by by the PSC.
	- If subsequent analysis yields a negative result, the assumption was incorrect.
	- Determining the "correct" voltage polarities and current directions before analysing the circuit is not worth it.

**Example**:
![[Lecture 1 - Basic Concepts 2024-09-05 15.25.47.excalidraw]]
![[Lecture 1 - Basic Concepts 2024-09-05 15.31.28.excalidraw]]![[Lecture 1 - Basic Concepts 2024-09-05 15.33.46.excalidraw]]
**Notation**
- Polarity of voltage is sometimes indicated by a subscript
- The first subscript indicates the higher-voltage node
- The second subscript indicates the lower-voltage node
- Voltages are often represented as relative to "ground"
	- Ground is a reference voltage which is written as 0V.
	- These voltages are not called a difference, they are assumed to be relative to zero volts.
	- Written with a single subscript.

### Power
- Measured in Watts
- $p=vi$
- Power is absorbed if the power is positive
- Power is generated if the power is negative

| ![[Lecture 1 - Basic Concepts 2024-09-05 15.44.58.excalidraw]] | ![[Lecture 1 - Basic Concepts 2024-09-05 15.46.25.excalidraw]] |
| :------------------------------------------------------------- | :------------------------------------------------------------- |
![[Lecture 1 - Basic Concepts 2024-09-05 15.49.57.excalidraw]]