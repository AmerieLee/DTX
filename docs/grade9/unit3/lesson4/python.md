# Python Activity
# Lesson 4 - Cybersecurity

## Learning Goal

Use Python to check whether a password meets basic security rules.

---

## Example Program

```python
password = input("Enter a password: ")

if len(password) >= 8:
    print("Password length: OK")
else:
    print("Password is too short.")
```

---

## Challenge 1

Modify the program to also check whether the password contains:

- At least one uppercase letter
- At least one number

---

## Challenge 2

Display:

- Strong Password
- Weak Password

based on your checks.

---

## Extension

Research Python's `any()` function and use it to simplify your program.
