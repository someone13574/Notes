[[ECOR1041_L03_variables_visualization.pdf]]
[[ECOR1041_L03_demo_script_variables.pdf]]

---
### Binary Addition

- Counting in decimal: 0, 1, 2, 3, 4, 5, 6, 7
- Counting in binary: 0, 1, 10, 11, 100, 101, 110, 111
- In binary: 1 + 1 = 10, or 0, carry 1
	- 1 + 1 + 1 = 11, or 1, carry 1
- Lets add $01010_2$ + $11111_2$
	- ![[Pasted image 20240912115900.png]]
	- Can double check by converting $01010_2$ ($10_{10}$) and $11111_2$ ($31_{10}$) to decimal and adding.

### Decimal to Binary Example

Convert 37 to binary:

- 37 - 32 = 5          1
-  16:                        0
- 8:                           0
- 5 - 4 = 1               1
- 2:                           0
- 1 - 1 = 0                1

### Fraction to Binary Example

- 0.375
- Int part
	- 0 -> 0
- Fractional Part
	- (0) $0.375 * 2 = 0.75$
	- (1) $0.75 * 2 = 1.5$
	- (1) $0.5 * 2 = 1.0$
		- $0.011_2$


# Variables

- In programming, a variable is a storage location in a computer's memory that contains a value and a symbolic name that is used to refer to the location.
- In python, variables are dynamically typed
- Naming conventions use `snake_case` (nobody calls it `pothole_case`)
- Spaces on either side of binary operators