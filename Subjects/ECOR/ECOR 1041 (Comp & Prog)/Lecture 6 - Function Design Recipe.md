[[ECOR1041_L06_design_recipe.pdf]]

---

## Steps

1. Examples
2. Header
3. Description
4. Body
5. Test

## Example

At an old-style movie theatre, every attendee pays $5 per ticket. Each performance costs the theatre $20 plus $0.50 per attendee. What is the net income (profit) for the theatre, given the number of attendees at a performance?

1. Examples
	- Choose a descriptive function name
	- Write some example function calls, showing the arguments and the return values
	- Put the examples in a documentation string (docstring)
```python
"""
>>> total_profit(5)
2.5
>>> total_profit(2)
-11.0
>>> total_profit(100)
430.0
"""
```

2. Header
	- Choose descriptive parameter names
	- Include type annotations in the function header
```python
def total_profit(attendees: int) -> float:
	"""
	Examples from above
	"""
```

3. Description
	- At the top of the docstring, write a summary of what the function does, in terms of its parameters, and what it returns (all on one line if possible).
		- Additional sentences may be needed to provide more information
	- Description what, not how
	- Uses preconditions do document any assumptions about permitted values of arguments
```python
def total_profit(attendees: int) -> float:
	"""Return the total profit of a movie performance,
	given the number of attendees.

	Precondition: attendees >= 0

	>>> total_profit(5)
	2.5
	>>> total_profit(2)
	-11.0
	>>> total_profit(100)
	430.0
	"""
```

4. Body
	- Design the function's algorithm, write the body
	- If you decide that the body should call functions that you have not yet developed, use the FDR to produce those functions
```python
PRICE_PER_TICKET = 5
FIXED_COST = 20
COST_PER_ATTENDEE = 0.50

def total_profit(attendees: int) -> float:
	"""Return the total profit of a movie performance,
	given the number of attendees.

	Precondition: attendees >= 0

	>>> total_profit(5)
	2.5
	>>> total_profit(2)
	-11.0
	>>> total_profit(100)
	430.0
	"""

	return (PRICE_PER_TICKET - COST_PER_ATTENDEE) * attendees - FIXED_COST
```

5. Test
	- Use at minimum the docstring examples copy/pasted into the shell
	- Consider coding a program to automate testing
		- Python provides `doctest` and `unittest` modules
		- 3rd-party testing frameworks such as `pytest`
