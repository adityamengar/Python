
| Priority | Operator            |        |
| :---     | :---                | :---   |
| 1        | `+`, `-`            | unary  |
| 2        | `**`                |        |
| 3        | `*`, `/`, `//`, `%` |        |
| 4        | `+`, `-`            | binary |
| 5        | `<`, `<=`, `>`, `>=`|        |
| 6        | `==`, `!=`          |        |


# Use these relational operators to compare values. They always evaluate to a boolean value (`True` or `False`)

| Operator | Description | Example |
| :--- | :--- | :--- |
| `==` | returns `True` if operands' values are equal, and `False` otherwise | `x == y  # False`<br>`x == z  # True` |
| `!=` | returns `True` if operands' values are not equal, and `False` otherwise | `x != y  # True`<br>`x != z  # False` |
| `>` | `True` if the left operand's value is greater than the right operand's value, and `False` otherwise | `x > y  # False`<br>`y > z  # True` |
| `<` | `True` if the left operand's value is less than the right operand's value, and `False` otherwise | `x < y  # True`<br>`y < z  # False` |
| `>=` | `True` if the left operand's value is greater than or equal to the right operand's value, and `False` otherwise | `x >= y  # False`<br>`x >= z  # True`<br>`y >= z  # True` |
| `<=` | `True` if the left operand's value is less than or equal to the right operand's value, and `False` otherwise | `x <= y  # True`<br>`x <= z  # True`<br>`y <= z  # False` |