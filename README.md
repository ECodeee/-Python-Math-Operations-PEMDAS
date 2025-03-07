# 🔢 Python Math Operations & PEMDAS

## 📌 Code Explanation
This code demonstrates basic mathematical operations and operator precedence in Python.

### ✅ Basic Operations
```python
print("My age: " + str(12))  # Converts integer to string before concatenation
print(123 + 456)  # Addition: 579
print(7 - 3)  # Subtraction: 4
print(3 * 2)  # Multiplication: 6
print(6 / 3)  # Division: 2.0 (Always returns a float)
print(2**3)  # Exponentiation: 2³ = 8
```

### 🔢 Operator Precedence (PEMDAS)
Python follows the **PEMDAS** order when evaluating expressions:

1. **Parentheses `()`** – Highest priority
2. **Exponents `**`**
3. **Multiplication `*`** (Left to Right)
4. **Division `/`** (Left to Right)
5. **Addition `+`** (Left to Right)
6. **Subtraction `-`** (Left to Right)

### ✅ Example of Operator Precedence
```python
result = 3 + 3 * 2  # Multiplication happens first: 3 + (3 * 2) = 3 + 6 = 9
print(result)  # Output: 9
```

This ensures correct order of operations in complex expressions! 🚀
