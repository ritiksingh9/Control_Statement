# Control_Statement
Control_Statement
# 📘 Control Statements in Python

## 📌 Overview

This project demonstrates the use of **control statements in Python**, which are essential for controlling the flow of execution in a program. Control statements allow decision-making, looping, and branching based on conditions.

---

## 🎯 Objectives

* Understand the concept of control statements
* Implement decision-making using `if`, `if-else`, and `if-elif-else`
* Learn looping constructs like `for` and `while`
* Use jump statements like `break`, `continue`, and `pass`

---

## 🧠 Types of Control Statements

### 🔹 1. Decision-Making Statements

Used to execute code based on conditions.

#### Example:

```python
age = 18

if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible")
```

---

### 🔹 2. Looping Statements

Used to execute a block of code repeatedly.

#### ➤ For Loop Example:

```python
for i in range(1, 6):
    print(i)
```

#### ➤ While Loop Example:

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

---

### 🔹 3. Jump Statements

Used to alter the flow of loops.

#### ➤ Break:

```python
for i in range(1, 10):
    if i == 5:
        break
    print(i)
```

#### ➤ Continue:

```python
for i in range(1, 6):
    if i == 3:
        continue
    print(i)
```

#### ➤ Pass:

```python
for i in range(1, 6):
    if i == 3:
        pass
    print(i)
```

---

## ⚙️ Requirements

* Python 3.x installed
* Any code editor (VS Code, PyCharm, etc.)

---

## ▶️ How to Run

1. Save the file as `control_statements.py`
2. Open terminal or command prompt
3. Run the program using:

```bash
python control_statements.py
```

---

## 📊 Applications

* Decision-making systems
* Game logic development
* Input validation
* Automation scripts

---

## ✅ Conclusion

Control statements are the backbone of programming logic. By mastering them, you can create efficient, dynamic, and intelligent programs in Python.

---

## 👨‍💻 Author

Ritik Kumar

