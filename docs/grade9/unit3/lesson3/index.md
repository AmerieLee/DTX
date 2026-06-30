# Grade 9 Digital Technology

# Unit 3 – Networks and the Internet

# Lesson 3 – Network Protocols

---

# Learning Objectives

By the end of this lesson, you will be able to:

- explain what a network protocol is
- describe why communication rules are important
- identify common Internet protocols
- distinguish between HTTP and HTTPS
- explain the basic role of TCP/IP
- recognise how protocols help computers communicate reliably

---

# Success Criteria

At the end of this lesson, you should be able to:

✅ define a network protocol.

✅ explain why computers need communication rules.

✅ identify several common Internet protocols.

✅ explain the difference between HTTP and HTTPS.

✅ describe how TCP helps deliver data reliably.

---

# Key Vocabulary

| Term | Meaning |
|------|---------|
| Protocol | A set of rules that devices follow when communicating. |
| TCP | A protocol that ensures data is delivered correctly. |
| IP | A protocol used to identify devices and route data across networks. |
| HTTP | A protocol used to transfer web pages. |
| HTTPS | A secure version of HTTP that encrypts data. |
| Packet | A small piece of data sent across a network. |
| Acknowledgement (ACK) | A message confirming that data has been received. |
| Encryption | Converting data into a secure form so only authorised users can read it. |

---

# Think About This

Imagine two people trying to play a board game.

One person follows the rules.

The other person invents new rules whenever they want.

### Questions

- Would the game work?
- Would it be fair?
- Would both players understand what to do?

Now imagine millions of computers trying to communicate without agreed rules.

Would the Internet work?

---

# Why Do Computers Need Rules?

People communicate using languages and social rules.

For example:

- We greet people politely.
- We take turns speaking.
- We listen before responding.

Computers also need rules.

These rules tell devices:

- when to send data
- where to send it
- how to organise information
- how to check for errors
- what to do if information is lost

These communication rules are called **network protocols**.

---

# What Is a Network Protocol?

A **network protocol** is a set of agreed rules that allows computers and other devices to communicate.

Protocols define:

- the format of messages
- the order of communication
- how errors are handled
- how devices identify each other
- how information is protected

Without protocols, devices would not understand one another.

---

# Everyday Analogy

Imagine sending a letter.

To arrive successfully, everyone follows agreed rules.

You must:

1. Write the correct address.
2. Place the letter in an envelope.
3. Attach a stamp.
4. Post it through the mail system.
5. Wait for delivery.

Because everyone follows the same process, the letter reaches the correct destination.

The Internet works in a similar way.

Protocols provide the rules that every device follows.

---

# Classroom Example

Your teacher says:

> "Write your name at the top of the page."

Everyone understands the instruction because everyone follows the same classroom rules.

Imagine if every student invented their own rule.

Some might write their name at the bottom.

Others might not write it at all.

Some could use symbols instead of letters.

The teacher would have difficulty identifying each student's work.

Computers face the same problem.

Protocols ensure every device communicates in the same way.

---

# Real-World Examples of Protocols

Protocols are used every day, even if you don't notice them.

| Activity | Protocol Example |
|----------|------------------|
| Visiting a website | HTTP or HTTPS |
| Sending an email | SMTP |
| Receiving an email | IMAP or POP3 |
| Streaming a video | TCP/IP and HTTPS |
| Browsing online | DNS + HTTP/HTTPS + TCP/IP |

Most online activities use several protocols working together.

---

# Activity 1 – Rules Everywhere

Complete the table.

| Situation | What are the rules? |
|-----------|---------------------|
| Playing football | |
| Crossing the road | |
| Classroom discussion | |
| Sending a text message | |
| Computers communicating | |

Discuss your answers with a partner.

---

# Think–Pair–Share

Imagine there were **no protocols** on the Internet.

What problems might occur?

Consider:

- websites
- online games
- video calls
- emails
- cloud storage

Write down three possible problems.

1. _______________________________________

2. _______________________________________

3. _______________________________________

---

# Key Idea

Remember:

> **Protocols are the shared rules that allow computers to communicate successfully.**

Without common rules:

- messages may be misunderstood
- information may be lost
- devices may not recognise one another
- the Internet would not function reliably

---

# Quick Check

Choose the best answer.

### 1.

A network protocol is:

A. A type of computer

B. A communication rule

C. An Internet cable

D. A web browser

---

### 2.

Why are protocols important?

A. They make computers heavier.

B. They provide rules for communication.

C. They increase screen size.

D. They store websites.

---

### 3.

True or False

Computers can communicate successfully even if every manufacturer uses completely different communication rules.

_________

---

# Looking Ahead

Now that you understand **why protocols are necessary**, the next section explains the most important protocol family on the Internet:

## TCP/IP

These protocols make reliable communication between billions of devices possible.

---

# TCP/IP – The Language of the Internet

The Internet is not controlled by one computer or one company.

Instead, billions of devices communicate by following the same set of rules.

The most important collection of these rules is called the **TCP/IP protocol suite**.

TCP/IP makes it possible for devices made by different manufacturers, running different operating systems, to communicate successfully.

Without TCP/IP, the Internet as we know it would not exist.

---

# Two Important Protocols

Although TCP/IP includes many protocols, two are especially important.

| Protocol | Main Job |
|----------|----------|
| **IP (Internet Protocol)** | Finds the destination and routes data across networks. |
| **TCP (Transmission Control Protocol)** | Ensures data arrives correctly and in the correct order. |

Think of IP as choosing the route to a destination.

Think of TCP as checking that every package arrives safely.

---

# Understanding IP

IP is responsible for delivering data to the correct device.

Every device connected to a network has an IP address.

When you visit a website:

1. DNS finds the website's IP address.
2. Your computer creates data packets.
3. IP decides where those packets should travel.
4. Routers forward the packets toward the destination.

IP focuses on **where** data should go.

It does **not** guarantee that every packet will arrive.

---

# Understanding TCP

TCP works together with IP.

While IP delivers packets, TCP checks that communication is reliable.

TCP performs several important tasks:

- divides large files into packets
- numbers each packet
- checks whether packets arrive
- requests missing packets again
- rebuilds the original message in the correct order

This makes Internet communication reliable even when networks are busy.

---

# Imagine Sending a Puzzle

Suppose you send a 500-piece jigsaw puzzle to a friend.

You place the pieces into several small boxes.

During delivery:

- one box is delayed
- another arrives first
- one box is damaged

Without organisation, rebuilding the puzzle would be difficult.

TCP solves this problem.

It numbers every "box" (packet), checks that each one arrives, and requests another copy if one is missing.

---

# Activity 2 – TCP or IP?

Decide which protocol is mainly responsible.

| Situation | TCP | IP |
|-----------|:---:|:--:|
| Choosing the destination | □ | □ |
| Checking for missing packets | □ | □ |
| Delivering data to the correct address | □ | □ |
| Reassembling packets | □ | □ |
| Requesting lost packets again | □ | □ |

Compare your answers with a partner.

---

# HTTP – Talking to Websites

When you open a website, your browser needs a way to communicate with the web server.

It uses **HTTP**, which stands for **HyperText Transfer Protocol**.

HTTP defines how:

- browsers request web pages
- servers send web pages
- messages are organised
- responses are returned

Without HTTP, web browsers would not know how to request webpages.

---

# A Simple HTTP Example

Your browser sends a request such as:

> "Please send me the homepage."

The web server replies:

> "Here is the webpage."

The browser then displays the page on your screen.

This conversation follows the rules of HTTP.

---

# HTTPS – A Safer Version of HTTP

Modern websites usually use **HTTPS** instead of HTTP.

The extra **S** stands for **Secure**.

HTTPS encrypts data before it is sent across the Internet.

Encryption protects information such as:

- passwords
- online banking details
- shopping payments
- personal messages

Whenever you see the padlock icon in your browser, HTTPS is helping to protect your connection.

---

# Why Is HTTPS Important?

Imagine sending a postcard.

Anyone handling the postcard can read the message.

Now imagine placing the message inside a locked envelope.

Only the intended recipient can read it.

HTTPS works like that locked envelope.

It helps protect information while it travels across the Internet.

---

# HTTP vs HTTPS

| HTTP | HTTPS |
|------|--------|
| Transfers web pages | Transfers web pages securely |
| No encryption | Uses encryption |
| Less secure | More secure |
| Rarely used for sensitive information | Used for banking, shopping and online accounts |

Today, almost every major website uses HTTPS.

---

# Activity 3 – Secure or Not?

For each situation, decide whether HTTPS is especially important.

| Activity | HTTPS Needed? |
|----------|:-------------:|
| Reading the weather forecast | □ |
| Online banking | □ |
| Logging into school email | □ |
| Online shopping | □ |
| Reading a public news article | □ |

Discuss your answers with your group.

---

# How Protocols Work Together

When you visit a website, several protocols work together.

A simplified sequence is:

1. Enter a web address.
2. DNS finds the IP address.
3. IP identifies the destination.
4. TCP manages reliable delivery.
5. HTTP or HTTPS transfers the webpage.
6. Your browser displays the content.

Each protocol has a different job.

Together, they make web browsing possible.

---

# Key Idea

No single protocol runs the Internet.

Instead, many specialised protocols work together, with each one performing a different task.

This teamwork makes Internet communication fast, reliable and secure.

---

# Transition

So far, you have learned **what each protocol does**.

Next, you will discover **how these protocols work together while data travels as packets across the network**, and why acknowledgements (ACKs) make communication reliable.


---

# Packets and Acknowledgements (ACK)

When data travels across a network, it is divided into many small **packets**.

Each packet contains part of the original message.

After a packet reaches its destination, the receiving device sends back an **Acknowledgement (ACK)**.

An ACK simply means:

> "I received this packet successfully."

If an ACK is not received within a certain time, TCP assumes the packet was lost and sends it again.

This process helps ensure reliable communication.

---

# Example: Downloading a File

Imagine downloading a large photo.

The file is divided into many packets.

```
Packet 1 ✓
Packet 2 ✓
Packet 3 ✗ (Lost)
Packet 4 ✓
Packet 5 ✓
```

Because Packet 3 did not arrive, the receiving device does not send an ACK for it.

TCP requests Packet 3 again.

Once it arrives, the complete file can be reassembled correctly.

This all happens automatically, often in just a fraction of a second.

---

# Why Reliability Matters

Reliable communication is essential for many online activities.

Examples include:

- online banking
- submitting homework
- sending emails
- cloud storage
- video conferencing
- software updates

Imagine if part of a banking transaction or homework submission disappeared during transmission.

TCP helps prevent these kinds of problems.

---

# Activity 4 – What Happens Next?

Complete the sequence.

1. Browser sends a request.

↓

2. __________________________

↓

3. Packets travel across the Internet.

↓

4. __________________________

↓

5. Browser displays the webpage.

Discuss your answers with a partner before checking as a class.

---

# Putting It All Together

The diagram below summarises what happens when you visit a website.

```
Type URL

↓

DNS finds the IP address

↓

IP identifies the destination

↓

TCP manages reliable delivery

↓

HTTP or HTTPS transfers the webpage

↓

Browser displays the webpage
```

Although each protocol performs a different task, they work together as one complete system.

---

# Review Activity

Match each protocol with its primary purpose.

| Protocol | Purpose |
|----------|---------|
| DNS | A. Secure web communication |
| IP | B. Finds the destination |
| TCP | C. Translates names into IP addresses |
| HTTP | D. Transfers web pages |
| HTTPS | E. Reliable delivery |

Write your answers below.

DNS → ______

IP → ______

TCP → ______

HTTP → ______

HTTPS → ______

---

# Key Summary

Remember these important ideas.

### Protocol

A set of rules for communication.

---

### IP

Identifies where data should go.

---

### TCP

Ensures data arrives correctly and in order.

---

### HTTP

Transfers webpages.

---

### HTTPS

Transfers webpages securely using encryption.

---

### DNS

Translates domain names into IP addresses.

---

# Real-World Connections

Protocols are used every day when you:

- search on Google
- watch YouTube
- play online games
- submit assignments
- send emails
- shop online
- use cloud storage
- stream music

Even though these activities look different, they all depend on common communication protocols.

---

# Reflection

Answer the following questions.

### 1.

Why do computers need protocols?

____________________________________________________

____________________________________________________

---

### 2.

What is the difference between TCP and IP?

____________________________________________________

____________________________________________________

---

### 3.

Why is HTTPS safer than HTTP?

____________________________________________________

____________________________________________________

---

### 4.

Which protocol do you think is the most important?

Explain your answer.

____________________________________________________

____________________________________________________

---

# Challenge Activity

Imagine you are designing a brand-new messaging app.

Create your own communication rules.

Think about:

- How will users identify each other?
- How will messages be organised?
- What happens if a message is lost?
- How will you protect private conversations?

Write three rules for your protocol.

1. _______________________________________

2. _______________________________________

3. _______________________________________

---

# Check Your Understanding

Choose the best answer.

### 1.

Which protocol is mainly responsible for reliable delivery?

A. DNS

B. HTTP

C. TCP

D. IP

---

### 2.

What is the purpose of HTTPS?

A. Store websites

B. Encrypt web communication

C. Replace IP addresses

D. Create Wi-Fi networks

---

### 3.

What does an ACK tell the sender?

A. The packet was received.

B. The packet was deleted.

C. The browser closed.

D. The server disconnected.

---

### 4.

Which protocol translates a domain name into an IP address?

A. HTTP

B. DNS

C. TCP

D. FTP

---

### 5.

True or False

Several different protocols work together whenever you visit a website.

_________

---

# Key Takeaways

By the end of this lesson, you should understand that:

- Protocols are agreed communication rules.
- Different protocols perform different tasks.
- IP identifies destinations.
- TCP ensures reliable communication.
- HTTP transfers webpages.
- HTTPS protects data with encryption.
- DNS translates names into IP addresses.
- Modern Internet communication depends on many protocols working together.

---

# Looking Ahead

In **Lesson 4**, you will explore **Cybersecurity Fundamentals**.

You will learn:

- common online threats
- passwords and authentication
- malware and phishing
- safe online behaviour
- protecting personal information

Understanding network protocols provides the foundation for learning how secure communication works.
