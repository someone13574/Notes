[[ECOR1041_L11_lists.pdf]]

---

- A list is a finite sequence of ordered values
	- Eg. 7, 4, 9, 12, 7, 2
- The same value may occur more than once; eg. two 7's
- The values are ordered: the 9 occurs after the 4 and before the 12
- A list is created by expressions separated by commas enclosed in brackets.
- A list in python stores references to objects.
- Items in a list are often called elements
- When creating a new list, the elements are expressions
- They do not have to be literal values
- An empty list is a list that has no elements
	- It can be created using the expression `[]`
- Indexing
	- Each element can be accessed by an integer index that indicates its position in the list
		- The first element is at index 0, second at 1, third 2, etc.
	- Negative indices count from the back. -1 is the last, -2 is the second last, etc.
- Lists are mutable
- The `len` function returns the number of elements in a list
- `del list[idx]`