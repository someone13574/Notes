[[ECOR1041_L05_defining_functions.pdf]]

---

### Function Declaration

- Declare a function with `def function_name(parameters) -> return_type:`
- The return type is optional
- The parameters must be declared if used. Types not needed.
- The body is indented


#### Example
```python
import math

def volume_of_sphere(radius):
	return 4 / 3 * math.pi * r ** 3
```

With type annotations
```python
import math

def volume_of_sphere(radius: float) -> float:
	return 4 / 3 * math.pi * r ** 3
```