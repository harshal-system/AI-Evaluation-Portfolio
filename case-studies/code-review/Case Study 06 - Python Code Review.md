# Case Study 06 – Evaluating AI-Generated Python Code

## Domain

Code Review

---

# Objective

Evaluate an AI-generated Python function for correctness, readability, maintainability, and potential improvements.

---

# User Prompt

Write a Python function that returns the largest number in a list.

---

# AI Response

```python
def largest_number(numbers):
    largest = numbers[0]

    for number in numbers:
        if number > largest:
            largest = number

    return largest
```

---

# Evaluation

| Criterion | Score | Comments |
|-----------|:----:|----------|
| Correctness | 5/5 | Works correctly for a non-empty list. |
| Readability | 5/5 | Variable names are clear. |
| Efficiency | 5/5 | Single pass through the list (O(n)). |
| Error Handling | 3/5 | Does not handle an empty list. |
| Maintainability | 5/5 | Easy to understand and modify. |
| Instruction Following | 5/5 | Fully answers the prompt. |
| Code Quality | 5/5 | Clean and well formatted. |

---

# Overall Score

**33 / 35 (94%)**

---

# Strengths

- Simple implementation.
- Efficient algorithm.
- Readable code.
- Good variable names.

---

# Weaknesses

- No validation for empty input.
- Could include a docstring.
- No type hints.

---

# Improved Code

```python
from typing import List

def largest_number(numbers: List[int]) -> int:
    """
    Return the largest number in a non-empty list.
    """
    if not numbers:
        raise ValueError("The list cannot be empty.")

    largest = numbers[0]

    for number in numbers:
        if number > largest:
            largest = number

    return largest
```

---

# Lessons Learned

- Validate user input.
- Add documentation.
- Use type hints for clarity.
- Handle edge cases.

---

# Final Recommendation

**Accept with Minor Improvements**

The algorithm is efficient and readable. Adding input validation and documentation makes it more robust and production-ready.