[[4. Single node circuits_F24.pdf]]

---

## Single Node Pair Circuits

- Circuits where all the elements have the same voltage across them.
	- (all the elements are in parallel)
	- ![[Pasted image 20240917143957.png]]
- Has only two nodes.
- Current will be different based on the resistance of elements

## Parallel Resistances

- The total resistance is less than the smallest resistance
- Adding another resistor will *always* decrease the total resistance, no matter the resistance of the path.
- Resistances in parallel are equivalent to
### $\frac{1}{R_P}=\frac{1}{R_1} + \frac{1}{R_2} + ... + \frac{1}{R_N}$

- Two resistors in parallel is given by
### $R_P = \frac{R_1 \times R_2}{R_1 + R_2}$

- N parallel resistors with equal resistance is given by
### $R_P = \frac{R}{N}$

### Current Divider

- The current though any resistor in a single node pair circuit with a current source can be found using a Current Divider

### $i_k(t) = \frac{R_P}{R_k}i_0(t)$

Where
- $i_k$ is the current through resistor k
- $R_P$ is the equivalent resistance to the resistors in parallel
- $R_k$ is the resistance of resistor k
- $i_k(t)$ is the current source

#### Special Case for Two Resistors

### $i_N = \frac{R_{N'}}{R_1 + R_2} \times i_0$

## Equivalent Current Sources

- Similar to our equivalent voltage sources in single loop circuits, we can make equivalent current sources.
- Assume currents entering are +ve and applying KCL
- Collect current source terms, using the sign of the net value to determine the direction of the equivalent source.