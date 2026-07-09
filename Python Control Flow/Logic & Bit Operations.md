# 'AND' OPERATOR
It's a binary operator with a priority that is lower than the one expressed by the comparison operators


| Argument A | Argument B | A and B |
| :--- | :--- | :--- |
| False | False | False |
| False | True | False |
| True | False | False |
| True | True | True |

# 'OR' OPERATOR
It's a binary operator with a lower priority than and (just like '+' compared to '*')


| Argument A | Argument B | A or B |
| :--- | :--- | :--- |
| False | False | False |
| False | True | True |
| True | False | True |
| True | True | True |

# 'NOT' OPERATOR
It's a unary operator performing a logical negation. Its operation is simple: it turns truth into falsehood and falsehood into truth.


| Argument | not Argument |
| :--- | :--- |
| False | True |
| True | False |

# Logical v/s Bitwise Operations
### 🔹 Logical vs. Bitwise Operations

#### **The Core Difference**
* **Logical Operators (`and`, `or`, `not`):** Treat the entire number as a single value (Zero = `False`, Non-Zero = `True`).
* **Bitwise Operators (`&`, `|`, `^`, `~`):** Compare each individual bit (0 or 1) of the binary numbers side-by-side.

#### **Example: `i = 15` and `j = 22`**
* **Binary Representation:**
  * `i`: `00000000000000000000000000001111`
  * `j`: `00000000000000000000000000010110`

#### **Comparison Table**

| Operation Type | Syntax | Calculation | Result |
| :--- | :--- | :--- | :--- |
| **Logical AND** | `i and j` | `True and True` | `True` |
| **Bitwise AND** | `i & j` | Aligns bits side-by-side | `6` (`0110`) |
| **Logical NOT** | `not i` | Changes `True` to `False` | `False` |
| **Bitwise NOT** | `~i` | Flips every single bit | `-16` (Two's Complement) |

#### **Abbreviated (Compound) Assignment Notations**
Instead of writing out the full math, you can use these shortcuts to update a variable in place:

* `i &= j` ➡️ Same as `i = i & j`
* `i |= j` ➡️ Same as `i = i \| j`
* `i ^= j` ➡️ Same as `i = i ^ j`
* `i <<= n` ➡️ Same as `i = i << n` (Shift bits left)
* `i >>= n` ➡️ Same as `i = i >> n` (Shift bits right)
