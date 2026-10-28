# Python Essentials — Module 2 Summary

**Course:** AkwanyaHub Python Essentials  
**Module:** 2 — Data Types, Output, Variables, and Expressions  
**Learner:** Josephine Amia
## Overview

In Module 2, I learned the foundations of writing Python instructions, displaying output, representing different kinds of data, storing values in variables, and performing calculations with operators. I practised these ideas by running small code examples and checking their output.

## 1. The `print()` function

The built-in `print()` function displays information in the console.

```python
print("Hello, Python!")
print("My name is", "Josephine")
```

The first line prints a message. The second prints two arguments, separated by a space by default.

I also learned about two useful `print()` keyword arguments:

- `sep` controls the separator between multiple arguments.
- `end` controls what is printed at the end. By default, it adds a newline.

```python
print("Learning", "Python", sep="***", end="!")
```

**Output:**
```text
Learning***Python!
```

## 2. Strings and escape characters

A string is text enclosed in single or double quotation marks. The `\n` escape sequence starts a new line.

```python
print("Learning\nPython")
print("I like \"Python\"")
```

**Output:**
```text
Learning
Python
I like "Python"
```

I learned that quotation marks must be used consistently and that a backslash can change the meaning of the character that follows it.

## 3. Python literals and data types

A literal is a value written directly in the code. Module 2 introduced these common types:

- **Integers (`int`)** — whole numbers, such as `12` or `-4`.
- **Floating-point numbers (`float`)** — numbers with a decimal part, such as `3.5` or `-0.4`.
- **Strings (`str`)** — text enclosed in quotation marks, such as `"Hello"`.
- **Booleans (`bool`)** — the logical values `True` and `False`.

```python
age = 7
height = 1.25
name = "Nehan"
is_learning = True

print(age, height, name, is_learning)
```

I learned that `7` is an integer, while `7.0` is a float. Although they may represent similar quantities, Python treats them as different data types.

## 4. Variables and assignment

A variable is a name used to refer to a value. Python creates a variable when a value is assigned to it.

```python
first_number = 10
second_number = 5

total = first_number + second_number
print(total)
```

**Output:**
```text
15
```

I learned that variable names should be meaningful, cannot be Python keywords, and are case-sensitive. For example, `total` and `Total` are different names.

Python is dynamically typed, so I do not have to declare a variable's type before assigning a value to it.

## 5. Operators and expressions

Operators perform actions on values. Module 2 covered arithmetic operations such as:

| Operator | Meaning | Example result |
|---|---|---|
| `+` | Addition | `5 + 2` gives `7` |
| `-` | Subtraction | `5 - 2` gives `3` |
| `*` | Multiplication | `5 * 2` gives `10` |
| `/` | Division | `5 / 2` gives `2.5` |
| `//` | Floor division | `5 // 2` gives `2` |
| `%` | Modulo (remainder) | `5 % 2` gives `1` |
| `**` | Exponentiation | `5 ** 2` gives `25` |

An expression combines values, variables, and operators to produce a result.

```python
x = 2
y = 3 * x**2 - 2 * x + 3
print(y)
```

**Output:**
```text
11
```

I also learned that operator precedence affects the order of calculations. Parentheses can be used to make the intended order clearer.

## 6. Shortcut assignment operators

Shortcut operators update a variable using its current value.

```python
score = 10
score += 5
score *= 2
print(score)
```

**Output:**
```text
30
```

Here, `score += 5` means the same as `score = score + 5`. Likewise, `score *= 2` means `score = score * 2`.

## 7. Combining text and values

I practised displaying text alongside variable values using `print()`.

```python
name = "Python"
version = 3
print("I am learning", name, "version", version)
```

This is useful when creating clear messages that include results from calculations or information stored in variables.

## 8. Practice and key takeaways

Through the examples and lab exercises, I practised printing messages, formatting output, working with strings and numbers, assigning values to variables, and calculating results.

My main takeaways were:

- `print()` displays information in the console.
- Strings use quotation marks, and `\n` creates a new line.
- Integers, floats, strings, and Booleans represent different kinds of data.
- Variables store values that can be reused and updated.
- Operators perform calculations, and precedence determines their order.
- Shortcut assignment operators make updates more concise.
- Running code and checking its output helps me learn and identify mistakes.

## Conclusion

Module 2 helped me understand how Python displays output, represents data, stores values, and performs calculations. I am building confidence by testing examples, observing the results, and correcting mistakes when they occur. I plan to keep practising these concepts as I move to the next module.

## Evidence to add

1. A code example using `print()`, `sep`, or `end`, with its output.
2. <img width="1174" height="915" alt="Module 2 -Hello Python" src="https://github.com/user-attachments/assets/ed1f363a-5591-49c5-b00b-e577ee9ef365" />

3. A code example showing variables and data types.
4. <img width="1170" height="937" alt="Module 2-Variables" src="https://github.com/user-attachments/assets/fd369cdf-1e70-4868-9d21-b14350322aad" />
<img width="1169" height="941" alt="Module 2- Var error" src="https://github.com/user-attachments/assets/7524bb37-b258-4de2-b21b-a62517a9bf10" />

5. An arithmetic expression or shortcut-operator example and its output.
<img width="1169" height="941" alt="Module 2- Var error" src="https://github.com/user-attachments/assets/95dc2e07-ff22-4d50-81c2-4f901f937150" />
<img width="1174" height="940" alt="Module 2- Operators" src="https://github.com/user-attachments/assets/eb734df4-8bcc-4570-a710-6c8be7ee477d" />

## Tags

`python` `learning-python` `python-essentials` `akwanyahub`
