[[ECOR1042_L03_dictionaries.pdf]]

---

- Learning Outcomes
	- Know the meaning of these words and phrases
		- Dictionary/map (type `dict`)
		- Key, value associated with a key, key/value pair, entry
	- Be able to evaluate expressions consisting of `dict` objects and some of the operations supported by that type
	- Understand the key differences between lists, tuples, sets, and dictionaries
- Dictionaries
	- A `dict` object is created by an expression of the form `{key1: val1, key2: val2, keyN: valN}`
	- Each key maps to a value
	- A key/value pair is also known as an entry
	- Keys are unique and immutable
	- Values do not need to be unique and can be mutable
	- The dictionary itself it mutable and ordered (by insertion time)
		- Only ordered as of python 3.7
		- Updating does not change order
	- The `in` operator checks for *keys* in a dictionary