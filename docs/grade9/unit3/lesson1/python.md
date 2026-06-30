# Python Lab
# Unit 3 – Networks and the Internet
## Lesson 1 – Introduction to Computer Networks

---

# Lab Overview

In this lab, you will use Python to represent a simple computer network.

You will learn how programming can help us organise, analyse, and simulate network information.

No previous programming experience is required.

---

# Learning Objectives

By the end of this lab, you will be able to:

- Create Python variables.
- Store network devices in a list.
- Count the number of devices.
- Use loops to display information.
- Modify a simple network model.

---

# Preparation

Before starting:

- Open Google Colab or VS Code.
- Create a new Python notebook.
- Save it as **lesson1_network_lab.ipynb**.

---

# Activity 1 – Your First Network

Type the following program.

```python
network = [
    "Teacher Computer",
    "Student Laptop",
    "Printer",
    "Router",
    "Switch"
]

print(network)
```

### Questions

1. How many devices are listed?

_________________________________________________

2. Which device connects different networks?

_________________________________________________

---

# Activity 2 – Printing Each Device

Instead of printing the whole list at once, print one device at a time.

```python
network = [
    "Teacher Computer",
    "Student Laptop",
    "Printer",
    "Router",
    "Switch"
]

for device in network:
    print(device)
```

### Challenge

Add these devices.

- Tablet
- Smartphone
- Smart TV

Run the program again.

How many devices are displayed now?

___________________________

---

# Activity 3 – Counting Devices

Python can count automatically.

```python
network = [
    "Teacher Computer",
    "Student Laptop",
    "Printer",
    "Router",
    "Switch"
]

print(len(network))
```

### Task

Add five more devices.

What is the new total?

______________

---

# Activity 4 – Is a Device Connected?

Python can check whether an item exists.

```python
network = [
    "Teacher Computer",
    "Student Laptop",
    "Printer",
    "Router",
    "Switch"
]

device = input("Enter a device name: ")

if device in network:
    print("Connected")
else:
    print("Not found")
```

### Try

Check:

- Printer
- Router
- Tablet

What happens?

_________________________________________________

---

# Activity 5 – Building Your Own Network

Create a list containing at least ten devices.

Example

```python
my_network = [
]
```

Include

- computers
- phones
- tablets
- printer
- router
- switch

Print every device.

---

# Extension Activity

Display each device with a number.

Expected output

```
1 Teacher Computer
2 Student Laptop
3 Printer
4 Router
5 Switch
```

Hint

Use

```python
enumerate()
```

---

# Mini Project – Design a School Network

Your school will purchase new equipment.

Create a Python list containing every device.

Example

```python
school_network = [
]
```

Requirements

Include at least

- 30 laptops
- teacher computer
- printer
- router
- switch
- Wi-Fi access point

You do **not** need to type 30 laptop names.

Instead, create a list that represents the different device types.

Then answer:

- Which device is the most important?
- Which device connects to the Internet?
- Which device allows wireless access?

---

# Reflection

Complete the following.

Today I learned...

____________________________________________________

____________________________________________________

The easiest activity was...

____________________________________________________

The most difficult activity was...

____________________________________________________

One thing I still want to learn is...

____________________________________________________

---

# Extension Challenge

Research one networking device that was **not** discussed in today's lesson.

Examples include:

- Firewall
- Modem
- Network Attached Storage (NAS)
- Load Balancer

Create a short presentation including:

- Name
- Picture
- Purpose
- Where it is used

Be prepared to share your findings with the class.
