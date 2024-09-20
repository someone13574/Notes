[[ECOR1041_L02_representing_numbers.pdf]]

---
## Modulus Review

- Modulus gives us the remainder when dividing one number, `m`, by another number, `n` (i.e. `m % n`)
- We will assume that `m` and `n` are integers (for now). 
- If the number, `n`, is positive, the possible remainders are 0, 1, 2, …, n - 1
- Example:
	- If we have `m % 3`, the remainder will be 0, 1, or 2.
- If the number, `n`, is negative, the possible remainder are 0, -1, -2, …, n + 1.
- Example
	- If we have `m % -3`, the remainder will be 0, -1, or -2.

![[Pasted image 20240910115910.png]]

### $-m\ \% -n = -(m\ \%\ n)$

### $m \% n = (m / n - floor(n/m)) * (n)$

### Floating Point

- The answer will be floating point
- If either ends with .0, then do the calculation as with ints and add .0 on the end of the answer.
- Otherwise, the rules will apply but you round to the number of decimal places in the original numbers.
- ##### You don't need to know this.

---
## Number Systems

- Notation: $\text{digits}_{\text{base}}$
	- 11 base 10: $11_{10}$
	- 11 base 2: $11_2$
- Storage:
	- Data is stored in "words" containing a fixed number of binary digits.
	- Numbers are padded with loading 0's if it requires fewer bits than the words size.
	- $11010_2$ is stored as:
		- 00011010 in an 8-bit word (a *byte*)
		- 0000000000011010 in a 16-bit word

#### Unsigned Binary Integers

- All bits contribute to the magnitude
- The smallest possible value is 0
- The maximum possible value is $2^k - 1$ where $k$ is the number of bits.
	- Unsigned 8-bit Integer: $11111111_2$ = $2^8 - 1 = 255_{10}$
- Binary to Decimal Conversion
	- Multiply each digit by its weight
	- Weights are powers of two
	- $d_3d_2d_1d_0$ (binary)
		- = $d_3 \times 2^3 + d_2 \times 2^2 + d_1 \times 2^1 + d_0 \times 2_0$ (decimal)
	- Examples
		- $1001011001_2 = 601_{10}$
- Decimal to Binary Conversion
	- What is the largest power of two that is smaller or equal to the number?
		- $512 = 2^9$
	- This means there is a 1 in the $2^9$ position (the $10^{\text{th}}$ digit from the right)
	- Subtract 512 from the number, giving 86.
	- Repeat until 0 is reached.

### Signed Magnitude

- The MSB is the sign bit
	- 0 = positive
	- 1 = negative
- The remaining bits represent the integer's magnitude.
- Can store from $-(2^{k - 1} - 1) \text{ to } 2^{k - 1} - 1$
- Drawbacks
	- Has two representations for 0 (positive and negative)
	- Circuits become more complex than two's complement.

---

## Floating Point

- Floating point approximates real numbers
- Python uses 64-bit floats
	- $(-1)^s \times 2^e \times m$
	- $s$ is the sign
	- Exponent $e$ has 10 bits
	- Significand $m$ has 53 bits.
### Decimal fractions

- Binary numbers can have a *binary point*
- Each digit to the right of the binary point is weighted by a negative power of 2
- $0.1011_2$
	> = $1 \times 2^{-1} + 0 \times 2^{-2} + 1 \times 2^{-3} + 1 \times 2^{-4}$
	> = $0.5_{10} + 0.125_{10} + 0.0625_{10}$
	> = $0.6875_{10}$
	
	![[Pasted image 20240910124254.png]]
	