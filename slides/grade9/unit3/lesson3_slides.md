# Grade 9 Digital Technology

# Unit 3 – Networks and the Internet

# Lesson 3 Slides

# Network Protocols

---

# Slide 1 — Title

## Network Protocols

### Unit 3 – Lesson 3

**How do computers know how to communicate?**

---

### Speaker Notes

Welcome students.

Remind them that in Lesson 2 they learned how information travels across the Internet.

Today's lesson explains **how computers agree on the rules** for communication.

---

# Slide 2 — Learning Objectives

By the end of today's lesson you will be able to:

- Explain what a network protocol is.
- Describe the roles of TCP and IP.
- Compare HTTP and HTTPS.
- Explain why packets and acknowledgements are important.

---

### Speaker Notes

Explain that students do **not** need to memorise every protocol.

Instead, they should understand the purpose of each one.

---

# Slide 3 — Think About It

### Imagine...

Everyone in this classroom starts talking at the same time.

- Who speaks first?
- How do we know whose turn it is?
- What happens if everyone uses different rules?

---

### Discussion

Why do groups need rules?

---

### Speaker Notes

Allow students to discuss for one or two minutes.

Guide them toward the idea that communication works best when everyone follows the same rules.

Connect this idea to computer networks.

---

# Slide 4 — Everyday Rules

We follow rules every day.

Examples:

- Traffic lights
- Classroom rules
- Sports rules
- Queueing in a line

Without rules:

❌ confusion

❌ mistakes

❌ accidents

---

### Speaker Notes

Emphasise that network protocols are similar.

They are simply communication rules for computers.

---

# Slide 5 — What Is a Network Protocol?

## Definition

A **network protocol** is a set of agreed rules that devices follow when sending and receiving data.

Protocols help devices:

- communicate
- understand each other
- exchange information correctly

---

### Speaker Notes

Ask students to repeat the key phrase:

> "A protocol is a set of communication rules."

---

# Slide 6 — Why Are Protocols Important?

Without protocols:

❌ Messages may be incomplete.

❌ Devices may misunderstand each other.

❌ Data may be lost.

With protocols:

✅ Reliable communication

✅ Correct order

✅ Shared understanding

---

### Speaker Notes

Relate this to human conversations.

If two people speak different languages without a translator, communication becomes difficult.

---

# Slide 7 — Meet the Main Protocols

Today we will learn about:

- DNS
- IP
- TCP
- HTTP
- HTTPS

Each protocol has a different job.

Together they make the Internet work.

---

### Speaker Notes

Students already know DNS from Lesson 2.

Explain that today's lesson focuses mainly on TCP, IP, HTTP, and HTTPS.

---

# Slide 8 — TCP vs IP

| TCP | IP |
|------|----|
| Reliable delivery | Finds the destination |
| Checks packets | Uses IP addresses |
| Requests missing packets | Routes data |

Remember:

**TCP = Delivery Manager**

**IP = Navigator**

---

### Speaker Notes

Use a simple analogy.

IP is like a GPS giving directions.

TCP is like a delivery company making sure every package arrives safely.

---

# Slide 9 — Think–Pair–Share

Imagine sending a jigsaw puzzle to a friend.

Questions:

- Would you number the pieces?
- What if one piece disappeared?
- How would your friend know something is missing?

Discuss with your partner for two minutes.

---

### Speaker Notes

Lead students toward the concepts of:

- packet numbers
- missing packets
---

# Slide 10 — Understanding IP

## What Does IP Do?

IP (Internet Protocol) is responsible for finding the destination.

Think of IP as a GPS.

It answers the question:

**"Where should this data go?"**

---

### Key Points

- Uses IP addresses
- Routes packets
- Finds the correct destination
- Does **not** check whether packets arrive

---

### Speaker Notes

Explain that IP focuses only on getting packets to the correct address.

It does not guarantee successful delivery.

---

# Slide 11 — Understanding TCP

## What Does TCP Do?

TCP (Transmission Control Protocol) makes communication reliable.

It answers the question:

**"Did every packet arrive safely?"**

---

### TCP Responsibilities

- Numbers packets
- Checks packet order
- Detects missing packets
- Requests retransmission
- Rebuilds the original message

---

### Speaker Notes

Remind students that TCP works together with IP.

IP sends the packets.

TCP checks the delivery.

---

# Slide 12 — Packets

Large messages are divided into smaller pieces.

These pieces are called **packets**.

Example

```
HELLO INTERNET
```

↓

```
Packet 1 → HELLO

Packet 2 → INTERNET
```

---

### Why Use Packets?

- Faster transmission
- Easier routing
- More reliable delivery

---

### Speaker Notes

Explain that almost everything on the Internet travels as packets.

---

# Slide 13 — Packet Numbers

Packets receive sequence numbers.

Example

| Packet | Data |
|---------|------|
| 1 | HELLO |
| 2 | INTERNET |
| 3 | CLASS |

Even if packets arrive in a different order, TCP can rebuild the message.

---

### Speaker Notes

Compare packet numbers to page numbers in a book.

---

# Slide 14 — ACK (Acknowledgement)

When a packet arrives safely,

the receiver sends an **ACK**.

ACK means:

"I received this packet."

Example

```
Packet 1

↓

ACK 1
```

---

### Speaker Notes

Explain that acknowledgements help the sender know whether packets arrived successfully.

---

# Slide 15 — Missing Packets

What happens if Packet 2 never arrives?

Example

```
Packet 1 ✓

Packet 2 ✗

Packet 3 ✓
```

TCP notices that Packet 2 is missing.

It asks for Packet 2 to be sent again.

---

### Speaker Notes

This is called **retransmission**.

Emphasise that this is why TCP is called a reliable protocol.

---

# Slide 16 — HTTP

HTTP stands for

**HyperText Transfer Protocol**

Its job is to transfer webpages between a web server and a browser.

HTTP is:

- fast
- common
- **not encrypted**

---

### Speaker Notes

Explain that HTTP can be suitable for public information where sensitive data is not involved.

---

# Slide 17 — HTTPS

HTTPS is the secure version of HTTP.

The extra **S** means:

**Secure**

HTTPS encrypts information while it travels across the Internet.

Examples

- Online banking
- Shopping websites
- Email login
- School accounts

---

### Speaker Notes

Point out the padlock icon shown in most browsers when using HTTPS.

---

# Slide 18 — HTTP vs HTTPS

| HTTP | HTTPS |
|------|--------|
| No encryption | Encrypted |
| Less secure | More secure |
| Public websites | Login & payment pages |
| Faster setup | Safer communication |

---

### Think About It

Why should online banking always use HTTPS?

---

### Speaker Notes

Guide students to answers such as:

- protects passwords
- protects payment details
- prevents data interception
- improves privacy
---

# Slide 19 — How Protocols Work Together

## Visiting a Website

When you open a website, several protocols work together.

```
Type URL
      ↓
DNS finds the IP address
      ↓
IP routes the packets
      ↓
TCP checks reliable delivery
      ↓
HTTP/HTTPS transfers the webpage
      ↓
Browser displays the page
```

---

### Speaker Notes

Emphasise that no single protocol does everything.

Each protocol has a specialised job, and together they make web communication reliable and efficient.

---

# Slide 20 — A Real Example

Imagine you visit:

```
https://www.wikipedia.org
```

What happens?

1. You type the URL.
2. DNS finds the IP address.
3. IP sends packets to the correct server.
4. TCP checks that every packet arrives.
5. HTTPS encrypts the communication.
6. Your browser displays the webpage.

---

### Speaker Notes

Walk through each step slowly.

Ask students which protocol is responsible at each stage.

---

# Slide 21 — Protocol Teamwork

| Protocol | Main Job |
|-----------|----------|
| DNS | Finds the IP address |
| IP | Routes packets |
| TCP | Reliable delivery |
| HTTP | Transfers webpages |
| HTTPS | Transfers webpages securely |

**Together, these protocols make the Internet work.**

---

### Speaker Notes

Remind students that this table summarises the entire lesson.

Encourage them to use it as a revision guide.

---

# Slide 22 — Class Activity

## Which Protocol?

Choose the correct protocol.

### Situation 1

A browser needs the IP address of a website.

Answer: __________

---

### Situation 2

One packet is missing.

Answer: __________

---

### Situation 3

A student logs into online banking.

Answer: __________

---

### Speaker Notes

Suggested answers:

1. DNS
2. TCP
3. HTTPS

Discuss why each answer is correct.

---

# Slide 23 — Quick Quiz

Choose the best answer.

### 1.

Which protocol identifies the destination?

A. TCP

B. IP

C. HTTPS

D. DNS

---

### 2.

Which protocol sends acknowledgements?

A. HTTP

B. TCP

C. DNS

D. IP

---

### 3.

Why is HTTPS important?

A. It makes websites colourful.

B. It encrypts communication.

C. It changes IP addresses.

D. It stores webpages.

---

### Speaker Notes

Allow students to answer individually before reviewing together.

Answers:

1. B
2. B
3. B

---

# Slide 24 — Think–Pair–Share

Discuss with your partner.

**Question**

Why do computers divide information into packets instead of sending one huge message?

Think of at least **two advantages**.

---

### Speaker Notes

Expected ideas:

- easier to resend missing data
- faster transmission
- more efficient routing
- improved reliability

---

# Slide 25 — Lesson Summary

Today you learned:

✅ A protocol is a communication rule.

✅ IP finds the destination.

✅ TCP ensures reliable delivery.

✅ HTTP transfers webpages.

✅ HTTPS encrypts communication.

✅ Several protocols work together whenever we use the Internet.

---

### Speaker Notes

Revisit the learning objectives from Slide 2 and check whether students feel confident with each one.

---

# Slide 26 — Exit Ticket

Before you leave, answer these questions.

1. What is one new thing you learned today?

_________________________________

2. Which protocol do you understand best?

_________________________________

3. Which protocol would you like to learn more about?

_________________________________

---

### Speaker Notes

Collect responses to identify concepts that may need review in the next lesson.

---

# Slide 27 — Looking Ahead

## Next Lesson

**Lesson 4 – Cybersecurity Fundamentals**

We will explore:

- Encryption
- Authentication
- Password Security
- Malware
- Phishing
- Safe Online Behaviour

Understanding network protocols helps us understand how data can be protected while travelling across the Internet.

---

### Speaker Notes

Conclude the lesson by connecting today's topic to cybersecurity.

Explain that protocols such as HTTPS already use encryption, providing a natural bridge to the next lesson.

Thank students for their participation and encourage them to review the protocol summary table before the next class.

- acknowledgements (ACKs)

Explain that these ideas will be explored in the next part of the lesson.
