[[ECOR1041_L08_Boolean_operators.pdf]]

---
- Boolean Operators
	- Keywords: `and`, `or`, `not`
	- Precedence
		- Not is highest
		- Then and
		- Then or
		- Boolean operators have higher precedence than relational operators
	- Not
		- Inverts
		- True -> False
		- False -> True
	- And
		- True if both operands are True
		- False if either operand is False
	- Or
		- True if any operands are True
		- False if all operands are False
	- Relational operators and boolean operators can be combined
		- `if x >= 1 and x <= 100`
		- Python also lets us chain conditions
			- `if 1 <= x <= 100`

| p     | q     | not p | p and q | p or q |
| :---- | :---- | :---- | :------ | :----- |
| True  | True  | False | True    | True   |
| True  | False | False | False   | True   |
| False | True  | True  | False   | True   |
| False | False | True  | False   | False  |

## Example: `sleep_in()`

```python
def sleep_in(weekday: bool, vacation: bool) -> bool:
	"""Return True if we can sleep in; otherwise return
	False. Parameter weekday is true if today is a
	weekday. Parameter vacation is True if we are on
	vacation.
	"""
	return not weekday or vacation
```

## Automated Testing in Python

- Unit Testing
	- Tests a single unit of source code in isolation
	- In Python, a unit is typically a file containing one or more closely-related functions
	- Goal: show that individual units are correct, before they are integrated with other units
- Manual testing
	- Good for quick confidence tests
	- Tedious and error prone
- Regression Testing
	- Change software can cause new errors
	- Rerun all tests are ensure that recent changes hasn't broken working code
- Automating Testing
	- Create a test program for each unit
	- The program has one or more test cases for each function in the unit
	- The program compares the actual outcomes with expected results
	- `assert` statements
		- Assert is a keyword
		- Has the form `assert bool_expr`
		- If `bool_expr` is `True`, the execution continues quietly
		- If it is false, the execution halts and an `AssertionError` is displayed
		- Do not directly compare `float`'s, use `abs(actual - expected) < epsilon` where epsilon is a small value such as 0.001