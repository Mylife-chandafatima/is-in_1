# 🔍 Difference Between `is` and `in` Operators in Python

Python provides several operators to work with objects and collections, and two commonly misunderstood ones are `is` and `in`. Here's a clear breakdown:

---

## ✅ 1. `is` Operator (Identity Operator)

* **Purpose:** Checks whether two variables point to the **same object** in memory.
* **Returns:** `True` if both variables refer to the same object, otherwise `False`.
* **Used For:** Identity comparison.

### Example:

```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)  # ✅ True (same memory reference)
print(a is c)  # ❌ False (different objects, same values)
```

---

## ✅ 2. `in` Operator (Membership Operator)

* **Purpose:** Checks whether a value exists **inside** a sequence (list, tuple, string, dictionary, etc.).
* **Returns:** `True` if the value is present, otherwise `False`.
* **Used For:** Membership testing.

### Example:

```python
numbers = [1, 2, 3, 4]
print(2 in numbers)     # ✅ True (2 is in the list)
print(5 in numbers)     # ❌ False

text = "Python"
print("Py" in text)     # ✅ True
```

---

## 🔑 Quick Summary

| Operator | Checks                                | Example        | Result     |
| -------- | ------------------------------------- | -------------- | ---------- |
| `is`     | Identity (same memory object)         | `a is b`       | True/False |
| `in`     | Membership (value exists in sequence) | `2 in [1,2,3]` | True/False |

---
n.

---

### ✅ Hashtags

\#Python #CodingTips #LearnPython #PythonForBeginners #Programming
