# Grade 9 Digital Technology

# Python Lab

# Unit 3 – Networks and the Internet

# Lesson 3 – Simulating Network Protocols with Python

---

# Lab Overview

In this lesson, you will use Python to simulate how data travels across a network.

Instead of sending real network traffic, you will create a simple model of how protocols such as **TCP** organise information into packets.

By the end of this lab, you will understand how computers:

- split data into packets
- number packets
- rebuild messages
- detect missing packets

---

# Learning Objectives

By completing this lab, you will be able to:

- use Python lists
- use loops
- write simple functions
- manipulate strings
- simulate packet transmission
- understand reliable communication

---

# Prerequisites

You should already know:

- variables
- strings
- lists
- loops
- functions
- printing output

No networking libraries are required.

---

# Starter Activity

Imagine sending this message:

```
HELLO INTERNET
```

Would computers send it as one enormous block?

Usually not.

Instead, they divide the message into smaller pieces called **packets**.

Today, you will simulate this process.

---

# Activity 1 – Splitting a Message

Create a new Python file.

Type the following code.

```python
message = "HELLO INTERNET"

packets = message.split()

print(packets)
```

Output

```
['HELLO', 'INTERNET']
```

The message has been divided into two simple packets.

---

# Challenge

Try changing the message.

Example:

```python
message = "PYTHON MAKES NETWORKS EASY"
```

What happens?

Record your observations.

____________________________________________________

____________________________________________________

---

# Activity 2 – Creating Numbered Packets

Real networks keep packets organised.

Let's number them.

```python
message = "HELLO INTERNET"

words = message.split()

for number, packet in enumerate(words, start=1):
    print(number, packet)
```

Output

```
1 HELLO
2 INTERNET
```

Each packet now has a sequence number.

This helps TCP rebuild information correctly.

---

# Understanding enumerate()

The function

```python
enumerate()
```

adds numbers to items in a list.

Example

```python
animals = ["cat", "dog", "bird"]

for number, animal in enumerate(animals, start=1):
    print(number, animal)
```

Output

```
1 cat
2 dog
3 bird
```

This idea is similar to numbering packets in a network.

---

# Activity 3 – Building Packet Objects

Instead of storing only words, store additional information.

```python
message = "HELLO INTERNET"

packets = []

for number, word in enumerate(message.split(), start=1):

    packet = {
        "number": number,
        "data": word
    }

    packets.append(packet)

print(packets)
```

Output

```
[
 {'number': 1, 'data': 'HELLO'},
 {'number': 2, 'data': 'INTERNET'}
]
```

Each packet now stores:

- a packet number
- the packet contents

---

# Activity 4 – Displaying Packets

Loop through the packets.

```python
for packet in packets:
    print(packet["number"], packet["data"])
```

Output

```
1 HELLO
2 INTERNET
```

This is much easier to read.

---

# Activity 5 – Rebuilding the Message

Suppose all packets arrive safely.

We can rebuild the original message.

```python
message = ""

for packet in packets:
    message += packet["data"] + " "

print(message)
```

Output

```
HELLO INTERNET
```

The receiver has reconstructed the original message.

---

# Mini Challenge

Try changing the sentence.

Examples:

```
NETWORKS ARE AMAZING
```

or

```
DIGITAL TECHNOLOGY IS FUN
```

Does your program still work?

If not, why?

Write your answer.

____________________________________________________

____________________________________________________

---

# Think About It

Why do you think computers number packets?

Write two reasons.

1.

____________________________________________________

2.

____________________________________________________

---

# Check Your Understanding

Answer the questions.

### 1.

Which Python data structure stores multiple packets?

_____________________________________

---

### 2.

Which function added packet numbers?

_____________________________________

---

### 3.

Why are packet numbers useful?

_____________________________________

_____________________________________

---

# Looking Ahead

So far, every packet has arrived successfully.

But what happens if one packet disappears?
---

# Activity 6 – Simulating Packet Loss

In real networks, packets do not always arrive successfully.

Let's simulate a missing packet.

```python
packets = [
    {"number": 1, "data": "HELLO"},
    {"number": 2, "data": "INTERNET"},
    {"number": 3, "data": "CLASS"}
]

# Simulate packet loss
del packets[1]

print(packets)
```

Output

```
[
 {'number': 1, 'data': 'HELLO'},
 {'number': 3, 'data': 'CLASS'}
]
```

Packet 2 has disappeared.

---

# Why Is This a Problem?

Try rebuilding the message.

```python
message = ""

for packet in packets:
    message += packet["data"] + " "

print(message)
```

Output

```
HELLO CLASS
```

The word **INTERNET** is missing.

This is why reliable communication is important.

---

# Activity 7 – Detecting Missing Packets

We can check whether every packet number is present.

```python
expected = [1, 2, 3]

received = []

for packet in packets:
    received.append(packet["number"])

for number in expected:
    if number not in received:
        print("Missing packet:", number)
```

Output

```
Missing packet: 2
```

This is similar to what TCP does before rebuilding a message.

---

# Activity 8 – Simulating an ACK

When a packet arrives successfully, the receiver sends an acknowledgement.

```python
packets = [
    {"number": 1, "data": "HELLO"},
    {"number": 2, "data": "INTERNET"},
    {"number": 3, "data": "CLASS"}
]

for packet in packets:
    print(f"Packet {packet['number']} received.")
    print(f"ACK {packet['number']} sent.\n")
```

Output

```
Packet 1 received.
ACK 1 sent.

Packet 2 received.
ACK 2 sent.

Packet 3 received.
ACK 3 sent.
```

In real networks, ACK messages tell the sender that packets arrived successfully.

---

# Activity 9 – Retransmitting a Missing Packet

Imagine packet 2 was lost.

The sender sends it again.

```python
received = [1, 3]

if 2 not in received:
    print("Packet 2 missing.")
    print("Resending packet 2...")
```

Output

```
Packet 2 missing.
Resending packet 2...
```

This simple simulation demonstrates one of TCP's key features.

---

# Activity 10 – Reordering Packets

Packets do not always arrive in order.

```python
packets = [
    {"number": 3, "data": "CLASS"},
    {"number": 1, "data": "HELLO"},
    {"number": 2, "data": "INTERNET"}
]
```

Sort them before rebuilding.

```python
packets.sort(key=lambda packet: packet["number"])

for packet in packets:
    print(packet)
```

Output

```
{'number': 1, 'data': 'HELLO'}
{'number': 2, 'data': 'INTERNET'}
{'number': 3, 'data': 'CLASS'}
```

TCP performs a similar task when packets arrive out of order.

---

# Activity 11 – Build a Simple Receiver

Complete the program.

```python
packets = [
    {"number": 1, "data": "DIGITAL"},
    {"number": 2, "data": "TECHNOLOGY"},
    {"number": 3, "data": "CLASS"}
]

message = ""

for packet in packets:
    __________________________

print(message)
```

**Challenge:** Fill in the missing line so the original message is rebuilt correctly.

---

# Extension Challenge

Modify the receiver so that it checks for missing packet numbers before rebuilding the message.

Hint:

- Create a list of expected numbers.
- Compare it with the received packet numbers.
- Display a warning if any packets are missing.

Example output:

```
Missing packet: 2

Cannot rebuild message.
```

---

# Debugging Practice

A student wrote this code.

```python
packets = [
    {"number":1,"data":"HELLO"},
    {"number":2,"data":"WORLD"}
]

message = ""

for packet in packets:
    message += packet["word"]

print(message)
```

### Questions

1. What is the error?

____________________________________________________

2. How can you fix it?

____________________________________________________

---

# Check Your Understanding

### 1.

Why do computers send ACK messages?

____________________________________________________

---

### 2.

What happens if an ACK is never received?

____________________________________________________

____________________________________________________

---

### 3.

Why is packet numbering important?

____________________________________________________

____________________________________________________

---

# Looking Ahead

You have now simulated:

- numbered packets
- missing packets
- acknowledgements
- retransmission
- packet ordering

In the final section, you will combine these ideas to build a **Mini TCP Simulator** that demonstrates the complete communication process.
---

# Activity 6 – Simulating Packet Loss

In real networks, packets do not always arrive successfully.

Let's simulate a missing packet.

```python
packets = [
    {"number": 1, "data": "HELLO"},
    {"number": 2, "data": "INTERNET"},
    {"number": 3, "data": "CLASS"}
]

# Simulate packet loss
del packets[1]

print(packets)
```

Output

```
[
 {'number': 1, 'data': 'HELLO'},
 {'number': 3, 'data': 'CLASS'}
]
```

Packet 2 has disappeared.

---

# Why Is This a Problem?

Try rebuilding the message.

```python
message = ""

for packet in packets:
    message += packet["data"] + " "

print(message)
```

Output

```
HELLO CLASS
```

The word **INTERNET** is missing.

This is why reliable communication is important.

---

# Activity 7 – Detecting Missing Packets

We can check whether every packet number is present.

```python
expected = [1, 2, 3]

received = []

for packet in packets:
    received.append(packet["number"])

for number in expected:
    if number not in received:
        print("Missing packet:", number)
```

Output

```
Missing packet: 2
```

This is similar to what TCP does before rebuilding a message.

---

# Activity 8 – Simulating an ACK

When a packet arrives successfully, the receiver sends an acknowledgement.

```python
packets = [
    {"number": 1, "data": "HELLO"},
    {"number": 2, "data": "INTERNET"},
    {"number": 3, "data": "CLASS"}
]

for packet in packets:
    print(f"Packet {packet['number']} received.")
    print(f"ACK {packet['number']} sent.\n")
```

Output

```
Packet 1 received.
ACK 1 sent.

Packet 2 received.
ACK 2 sent.

Packet 3 received.
ACK 3 sent.
```

In real networks, ACK messages tell the sender that packets arrived successfully.

---

# Activity 9 – Retransmitting a Missing Packet

Imagine packet 2 was lost.

The sender sends it again.

```python
received = [1, 3]

if 2 not in received:
    print("Packet 2 missing.")
    print("Resending packet 2...")
```

Output

```
Packet 2 missing.
Resending packet 2...
```

This simple simulation demonstrates one of TCP's key features.

---

# Activity 10 – Reordering Packets

Packets do not always arrive in order.

```python
packets = [
    {"number": 3, "data": "CLASS"},
    {"number": 1, "data": "HELLO"},
    {"number": 2, "data": "INTERNET"}
]
```

Sort them before rebuilding.

```python
packets.sort(key=lambda packet: packet["number"])

for packet in packets:
    print(packet)
```

Output

```
{'number': 1, 'data': 'HELLO'}
{'number': 2, 'data': 'INTERNET'}
{'number': 3, 'data': 'CLASS'}
```

TCP performs a similar task when packets arrive out of order.

---

# Activity 11 – Build a Simple Receiver

Complete the program.

```python
packets = [
    {"number": 1, "data": "DIGITAL"},
    {"number": 2, "data": "TECHNOLOGY"},
    {"number": 3, "data": "CLASS"}
]

message = ""

for packet in packets:
    __________________________

print(message)
```

**Challenge:** Fill in the missing line so the original message is rebuilt correctly.

---

# Extension Challenge

Modify the receiver so that it checks for missing packet numbers before rebuilding the message.

Hint:

- Create a list of expected numbers.
- Compare it with the received packet numbers.
- Display a warning if any packets are missing.

Example output:

```
Missing packet: 2

Cannot rebuild message.
```

---

# Debugging Practice

A student wrote this code.

```python
packets = [
    {"number":1,"data":"HELLO"},
    {"number":2,"data":"WORLD"}
]

message = ""

for packet in packets:
    message += packet["word"]

print(message)
```

### Questions

1. What is the error?

____________________________________________________

2. How can you fix it?

____________________________________________________

---

# Check Your Understanding

### 1.

Why do computers send ACK messages?

____________________________________________________

---

### 2.

What happens if an ACK is never received?

____________________________________________________

____________________________________________________

---

### 3.

Why is packet numbering important?

____________________________________________________

____________________________________________________

---

# Looking Ahead

You have now simulated:

- numbered packets
- missing packets
- acknowledgements
- retransmission
- packet ordering

In the final section, you will combine these ideas to build a **Mini TCP Simulator** that demonstrates the complete communication process.
---

# Mini Project – Build a Simple TCP Simulator

In this project, you will combine everything you have learned to simulate a simple version of TCP communication.

Your program will:

- create packets
- display packet numbers
- simulate acknowledgements (ACKs)
- rebuild the original message

---

## Step 1 – Create the Packets

```python
message = "NETWORK PROTOCOLS ARE IMPORTANT"

packets = []

for number, word in enumerate(message.split(), start=1):
    packets.append({
        "number": number,
        "data": word
    })
```

---

## Step 2 – Send the Packets

```python
print("Sending packets...\n")

for packet in packets:
    print(f"Packet {packet['number']}: {packet['data']}")
```

Example output

```
Sending packets...

Packet 1: NETWORK
Packet 2: PROTOCOLS
Packet 3: ARE
Packet 4: IMPORTANT
```

---

## Step 3 – Receive the Packets

```python
print("\nReceiving packets...\n")

for packet in packets:
    print(f"Packet {packet['number']} received.")
    print(f"ACK {packet['number']} sent.")
```

---

## Step 4 – Rebuild the Message

```python
message = ""

for packet in packets:
    message += packet["data"] + " "

print("\nFinal message:")
print(message)
```

Example output

```
Final message:

NETWORK PROTOCOLS ARE IMPORTANT
```

Congratulations!

You have created a simple simulation of reliable packet transmission.

---

# Challenge 1 – Missing Packet

Remove one packet before rebuilding the message.

Example:

```python
del packets[2]
```

Questions

- Which packet disappeared?
- What information is missing?
- How could TCP solve this problem?

Write your answers below.

____________________________________________________

____________________________________________________

____________________________________________________

---

# Challenge 2 – Out-of-Order Packets

Shuffle the packet order.

```python
packets = [
    {"number": 3, "data": "ARE"},
    {"number": 1, "data": "NETWORK"},
    {"number": 4, "data": "IMPORTANT"},
    {"number": 2, "data": "PROTOCOLS"}
]
```

Sort the packets before rebuilding the message.

Hint:

```python
packets.sort(key=lambda packet: packet["number"])
```

Explain why sorting is necessary.

____________________________________________________

____________________________________________________

---

# Extension Challenge

Improve your simulator by adding one or more of the following features.

☐ Display the total number of packets.

☐ Detect duplicate packet numbers.

☐ Display missing packet numbers.

☐ Count how many ACKs were sent.

☐ Allow the user to enter their own message using `input()`.

Example:

```python
message = input("Enter a message: ")
```

---

# Reflection

Answer the following questions.

### 1.

How does packet numbering help communication?

____________________________________________________

____________________________________________________

---

### 2.

Why are acknowledgements (ACKs) important?

____________________________________________________

____________________________________________________

---

### 3.

What would happen if packets were never reordered?

____________________________________________________

____________________________________________________

---

### 4.

Which activity helped you understand TCP the most?

____________________________________________________

____________________________________________________

---

# Debugging Challenge

The program below contains several mistakes.

```python
packets = [
    {"number":1,"data":"HELLO"},
    {"number":2,"data":"WORLD"}
]

message = ""

for packet in packet:
    message += packet["data"]

print(messages)
```

Find and correct the errors.

| Error | Correction |
|--------|------------|
| | |
| | |
| | |

---

# Summary

In this lab, you learned how to simulate key ideas behind TCP using Python.

You practised:

- splitting messages into packets
- numbering packets
- rebuilding messages
- detecting missing packets
- simulating acknowledgements (ACKs)
- reordering packets

Although this is only a simplified model, it demonstrates the same ideas used by real computer networks.

---

# Key Vocabulary Review

Match each term with its meaning.

| Term | Meaning |
|------|---------|
| Packet | A. Confirmation that data arrived |
| ACK | B. Small piece of data |
| Protocol | C. Communication rules |
| TCP | D. Reliable delivery |

---

# Self-Assessment

Rate your confidence.

| Skill | 😊 | 😐 | ☹ |
|-------|:--:|:--:|:--:|
| I can split a message into packets. | ☐ | ☐ | ☐ |
| I can number packets. | ☐ | ☐ | ☐ |
| I understand ACKs. | ☐ | ☐ | ☐ |
| I can rebuild a message. | ☐ | ☐ | ☐ |
| I understand why TCP is reliable. | ☐ | ☐ | ☐ |

---

# Looking Ahead

In **Lesson 4**, you will explore **Cybersecurity Fundamentals**.

You will discover how encryption, authentication, strong passwords, and safe online behaviour help protect information on modern computer networks.

The packet communication model you built today provides the foundation for understanding secure digital communication.

---

# Optional Extension

Research one of the following topics.

- UDP
- FTP
- SSH
- SMTP
- IPv6

Create a one-page summary that explains:

1. What is it?
2. What is it used for?
3. How is it different from TCP or HTTP?

In the next section, you will simulate **TCP reliability**, including missing packets, acknowledgements (ACKs), and retransmission.

