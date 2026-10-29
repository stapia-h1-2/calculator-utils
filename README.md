# calculator-utils

Simple calculator utility library providing `add`, `subtract`, `multiply`, and
`divide` operations for integers and floating-point numbers.

```python
from calculator import add, divide, multiply, subtract

add(2, 3)       # 5
subtract(5, 2)  # 3
multiply(4, 3)  # 12
divide(7, 2)    # 3.5
```

`divide` uses true division and raises `ZeroDivisionError` when the divisor is
zero. Run the tests with `python -m unittest`.
