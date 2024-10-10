[[ECOR1041_L07_if_statements.pdf]]

---

- Type `bool`
	- Has value of `True` or `False`
	- Uppercase
- Comparison (relational) operators
	- >, <
		- Greater than, less than
	- >=, <=
		- Greater equal, less equal
	- ==
		- Equality
	- !=
		- Not equal to
- Control Flow
	- The order of which statements in a program are executed
- Control flow statements
	- Decide of control flow based on a conditional
	- Includes loops and conditional statements
	- `if-elif-else`
- If-else statement
```python
if condition:
	statement_a
else:
	statement_b
```

### Example: Abs
```python
fn abs(x):
	return x if x >= 0 else -x
```

or...

```python
def abs(x):
	if x >= 0:
		return x
	return -x
```

or...

```python
def abs(x):
	if x >= 0:
		return x
	else:
		return -x
```
