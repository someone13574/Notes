[[ECOR1041_L02_lists_tuples_sets.pdf]]

---

- Learning outcomes
	- Know the meaning of:
		- Lists, tuples, and sets
		- Ordered collections, unordered collections
		- Mutable collections, immutable collections
	- Be able to evaluate expressiosn consisting of `list`, `tuple`, and `set` objects and operations supported by those types
	- Understand the key differences between lists, tuples, and sets.


|                    | Strings | Lists | Sets | Tuples |
| :----------------- | :------ | :---- | :--- | :----- |
| Ordered            | Yes     | Yes   | No   | Yes    |
| Mutable            | No      | Yes   | Yes  | No     |
| Duplicates allowed | Yes     | Yes   | No   | Yes    |
| Notation           | `""`    | `[]`  | `{}` | `()`   |

- Lists
	- A finite sequence of values
	- In Python a list stores references to objects
	- These objects do not need to be the same type
	- Lists are mutable in Python
	- Lists are ordered in Python
	- Slicing
		- Creates a new list with consecutive elements of the original list from i to j (excluded).
		- If `i` isn't written, go from the beginning
		- If `j` is omitted, go to the end
		- Example: `[5, 2, 6, 2][1:3]` -> `[2, 6]`
- Aliasing
	- Two variables are aliases if they refer to the same object
	- The equal operator alias an variable unless it is part of a larger expression