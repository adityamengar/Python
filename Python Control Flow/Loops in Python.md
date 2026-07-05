## 3.2.16 Section Summary: Python Loops

### 1. Types of Loops
* **`while` Loop:** Runs continuously as long as a specific condition remains true. It is ideal when you don't know the exact number of iterations in advance.
* **`for` Loop:** Iterates a specific number of times over a sequence (such as a string, list, or collection) or a generated range of numbers.

### 2. Loop Control Statements
* **`break`:** Instantly exits and terminates the entire loop, moving program execution to the next section of code outside the loop.
* **`continue`:** Skips the rest of the current turn (iteration) and jumps straight to the beginning of the next loop cycle.

### 3. The `else` Clause in Loops
* In Python, both `while` and `for` loops can be paired with an optional `else` block.
* The `else` section only triggers if the loop runs to natural completion. If the loop is forcefully stopped by a `break` statement, the `else` block is skipped entirely.

### 4. The `range()` Function
Generates a sequence of integers used for counting or loop control. It accepts up to three parameters:
* **Start:** The starting number of the sequence (defaults to `0` if left blank).
* **Stop:** The end limit of the sequence. **Crucial note:** This target number itself is excluded from the final output.
* **Step:** The interval or gap between each number in the sequence (defaults to `1`, but can be negative for counting backward).