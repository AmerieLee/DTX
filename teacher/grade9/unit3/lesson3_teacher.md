# Grade 9 Digital Technology

# Teacher Guide

# Unit 3 – Networks and the Internet

# Lesson 3 – Network Protocols

---

# Lesson Overview

**Lesson Length**

70–80 minutes

**Focus**

Students learn that computers communicate by following agreed rules called **network protocols**. They explore the roles of TCP, IP, HTTP, HTTPS, and DNS, and understand how these protocols work together to enable reliable and secure Internet communication.

Rather than memorising technical definitions, students develop a conceptual understanding of why communication rules are necessary and how different protocols perform specialised tasks.

---

# Curriculum Connections

This lesson develops students' understanding of:

- digital communication
- computer networks
- Internet technologies
- cybersecurity foundations
- problem solving
- computational thinking
- digital literacy

Students also strengthen analytical thinking through comparisons, discussions, and real-world case studies.

---

# Learning Objectives

By the end of the lesson, students should be able to:

- define a network protocol
- explain why communication rules are necessary
- identify the roles of TCP and IP
- distinguish between HTTP and HTTPS
- explain the purpose of acknowledgements (ACKs)
- describe how several protocols work together when loading a webpage

---

# Success Criteria

Students can successfully:

✓ explain a protocol using their own words

✓ identify the purpose of TCP

✓ identify the purpose of IP

✓ explain why HTTPS is more secure than HTTP

✓ describe the sequence of events when visiting a website

---

# Prior Knowledge

Students should already understand:

- LAN and WAN
- routers and switches
- client and server
- packets
- IP addresses
- DNS
- webpage loading process

If students struggle with these concepts, briefly review Lesson 1 and Lesson 2 before introducing TCP/IP.

---

# Resources Required

Presentation

- lesson3_slides.md

Student Book

- lesson3/index.md

Workbook

- lesson3_workbook.md

Assessment

- lesson3_quiz.md

Visual Resources

- protocol-stack.svg
- tcp-vs-udp.svg
- http-request.svg
- packet-acknowledgement.svg
- protocol-comparison.svg

Datasets

- protocol_messages.csv
- network_packets.csv

---

# Key Vocabulary

| Word | Teacher Explanation |
|------|----------------------|
| Protocol | Agreed communication rules |
| TCP | Makes communication reliable |
| IP | Finds the correct destination |
| HTTP | Transfers webpages |
| HTTPS | Secure version of HTTP |
| Encryption | Protects information from being read by others |
| ACK | Confirmation that a packet arrived safely |

Encourage students to explain these terms using everyday language before introducing more formal definitions.

---

# Common Student Misconceptions

## Misconception 1

"TCP and IP are the same thing."

Clarify that:

IP decides **where** information travels.

TCP checks **whether** information arrives correctly.

---

## Misconception 2

"HTTPS makes websites faster."

Explain that HTTPS primarily improves **security**, not speed.

---

## Misconception 3

"Only one protocol is used when visiting a website."

Students should understand that many protocols work together simultaneously.

---

## Misconception 4

"Encryption hides websites from the Internet."

Clarify that encryption protects the contents of communication rather than making the website invisible.

---

# Suggested Lesson Timeline

| Time | Activity |
|------|----------|
| 10 min | Starter discussion |
| 15 min | Introduction to protocols |
| 15 min | TCP and IP |
| 15 min | HTTP vs HTTPS |
| 15 min | Activities and formative assessment |
| 10 min | Review and reflection |

Adjust timings according to student confidence and class discussion.

---

# Teaching Notes

## Slides 1–2

### Lesson Introduction

Begin by asking:

> "What would happen if everyone invented their own traffic rules?"

Allow students to suggest possible problems.

Examples:

- accidents
- confusion
- traffic jams
- unsafe roads

Explain that computers face a similar challenge.

Without shared communication rules, devices would not understand one another.

Introduce the term **protocol**.

---

## Slide 3

### Think About This

Students compare classroom rules, sports rules, and communication rules.

Encourage multiple examples.

Possible prompts:

- Why do games have rules?
- Why do schools have rules?
- Why does language have grammar?

Guide students toward the idea that rules make communication predictable and reliable.

---

## Slides 4–5

### Introducing Protocols

Key message:

A protocol is **not software**.

A protocol is **a set of agreed rules**.

Use familiar examples.

Possible analogy:

Different countries may drive on different sides of the road, but everyone within that country follows the same rules.

Similarly, every Internet-connected device follows common networking rules.

---

## Slides 6–7

### Everyday Examples

Ask students:

"What protocols do people use every day?"

Possible answers include:

- saying "hello"
- taking turns speaking
- classroom routines
- sports rules
- queueing politely

Explain that computers also need communication routines.

Transition naturally into networking protocols.

---

## Slides 8–9

### Transition to TCP/IP

Remind students:

Lesson 2 explained:

- DNS
- IP addresses
- webpage loading

Today's lesson answers a different question:

> "How do computers know exactly how to communicate?"

Introduce TCP/IP as the most important collection of Internet communication protocols.

Do not explain every detail yet.

Simply provide the overall idea before exploring each protocol individually in the next section.

---

# Teacher Tips

Keep technical language simple.

Instead of saying:

> "Transmission Control Protocol establishes reliable end-to-end communication."

Say:

> "TCP checks that every piece of information arrives safely."

Students remember ideas much more effectively than complex terminology.

---

# Formative Assessment Checkpoint

Before moving to TCP/IP, ask students to answer these questions orally:

1. What is a protocol?

2. Why do computers need protocols?

3. Can you think of an example of rules outside computing?

Listen for conceptual understanding rather than memorised definitions.
---

# Teaching Notes

## Slides 10–11

### Understanding IP

Begin by reviewing IP addresses from Lesson 2.

Ask students:

> "How does your computer know where to send information?"

Expected responses:

- It uses an IP address.
- DNS finds the IP address.
- Routers help send data.

Explain that **IP (Internet Protocol)** is responsible for finding the destination.

Emphasise that IP focuses on **where** data should travel, not whether every packet arrives successfully.

Avoid introducing IPv4 and IPv6 technical details at this stage.

The goal is conceptual understanding.

---

## Slides 12–13

### Understanding TCP

Introduce TCP by asking students:

> "What happens if one packet disappears while downloading a file?"

Allow students to predict possible problems.

Guide them toward these ideas:

- incomplete files
- broken images
- corrupted videos
- missing information

Explain that TCP prevents these problems by:

- numbering packets
- checking delivery
- requesting missing packets again
- rebuilding information in the correct order

Students should understand that TCP improves **reliability**, not speed.

---

## Demonstration

Prepare ten numbered cards.

Ask ten volunteers to stand in order.

Next:

- swap two students
- remove one student
- ask the class whether the "message" is complete

Explain that TCP identifies missing information and restores the correct order.

This simple activity usually creates a lasting understanding.

---

## Slides 14–15

### HTTP

Ask students:

> "When you type a website address, how does your browser ask for the webpage?"

Introduce HTTP.

Explain that HTTP defines:

- how requests are written
- how servers respond
- how webpages are transferred

Students do not need to memorise message formats.

Instead, focus on the idea that both the browser and the server follow agreed communication rules.

---

## HTTPS

Display two examples:

```
http://example.com
```

and

```
https://example.com
```

Ask:

> "What difference do you notice?"

Most students recognise the extra **S**.

Explain that:

**S = Secure**

Discuss why security matters.

Examples:

- online banking
- shopping
- school accounts
- email
- passwords

Students should understand that HTTPS protects information while it travels across the Internet.

---

## Demonstration

Show two envelopes.

One is open.

One is sealed.

Ask:

> "Which one would you use to send your password?"

Students immediately understand the purpose of encryption.

Connect the analogy directly to HTTPS.

---

## Slides 16–18

### Comparing Protocols

Present the following simplified table.

| Protocol | Main Job |
|-----------|----------|
| DNS | Finds IP addresses |
| IP | Finds the destination |
| TCP | Reliable delivery |
| HTTP | Transfers webpages |
| HTTPS | Transfers webpages securely |

Encourage students to compare similarities and differences.

Avoid asking students to memorise every definition.

Instead, ask:

> "What unique job does each protocol perform?"

---

# Higher-Order Questions

Use questions that require explanation rather than recall.

Examples:

- Why can't every company invent its own Internet rules?

- Why do you think TCP and IP are separate protocols?

- Would HTTPS still work without TCP?

- Why is reliable communication important?

- Which protocol do you think users notice the least?

Encourage students to justify their reasoning.

---

# Differentiation

## Support

Provide partially completed diagrams.

Highlight key vocabulary before reading.

Allow students to work in pairs.

Use visual aids frequently.

Provide sentence starters.

Examples:

- "TCP is responsible for..."

- "HTTPS is safer because..."

---

## Extension

Challenge students to investigate:

- FTP
- SMTP
- POP3
- IMAP

Ask:

"What job does each protocol perform?"

Students may create a comparison table or short presentation.

---

# Classroom Discussion

Possible discussion prompt:

> "Which protocol would cause the biggest problems if it disappeared tomorrow?"

Students may argue for:

- DNS
- TCP
- HTTPS
- IP

There is no single correct answer.

Focus on evidence-based reasoning.

---

# Formative Assessment

Check understanding after introducing TCP and HTTP.

Students complete the following statements.

- IP is responsible for ______________________.

- TCP ensures ______________________________.

- HTTPS is different because ________________.

Walk around the classroom.

Address misconceptions immediately.

---

# Common Misconceptions During Activities

If students say:

> "TCP sends data."

Clarify:

TCP manages reliable delivery.

IP actually delivers packets across networks.

---

If students say:

> "HTTPS protects my computer."

Clarify:

HTTPS protects data while it is travelling.

It does not replace antivirus software or strong passwords.

---

If students confuse DNS and HTTP:

Review the sequence.

```
URL

↓

DNS

↓

IP Address

↓

TCP/IP

↓

HTTP or HTTPS

↓

Browser
```

Repeat this sequence several times throughout the lesson.

---

# Teacher Tip

Students often try to memorise protocol names.

Instead, encourage them to remember each protocol's **main responsibility**.

If students understand the overall communication process, they can usually recall the protocol names naturally.

---

# Transition

Before moving to the final section, ask:

> "Imagine one packet disappears while watching YouTube."

"What should happen next?"

Use this discussion to introduce acknowledgements (ACKs) and packet retransmission in the final part of the lesson.
---

# Teaching Notes

## Slides 19–21

### Packets and Acknowledgements (ACK)

Remind students that a large file is not normally sent as one continuous block.

Instead, it is divided into many small packets.

Ask:

> "How does the sender know whether a packet arrived?"

Introduce the idea of an **Acknowledgement (ACK)**.

An ACK is a short confirmation message that tells the sender:

> "I received this packet."

If no ACK is received, TCP assumes the packet was lost and sends it again.

Students do not need to learn timing mechanisms or retransmission algorithms. Focus on the concept of reliable communication.

---

## Classroom Demonstration

Materials:

- 10 numbered cards
- One envelope or folder

Procedure:

1. Give each card to a different student.
2. Ask students to stand in numerical order.
3. Secretly remove one card.
4. Ask the class:
   - "What is missing?"
   - "Can we rebuild the message?"
5. Replace the missing card.

Explain that TCP behaves similarly by requesting missing packets before rebuilding the complete message.

---

## Slides 22–23

### Protocols Working Together

Display the complete communication sequence.

```
User enters URL
        ↓
DNS finds IP address
        ↓
IP identifies destination
        ↓
TCP manages reliable delivery
        ↓
HTTP/HTTPS transfers data
        ↓
Browser displays webpage
```

Emphasise that no single protocol performs every task.

Instead, Internet communication depends on multiple specialised protocols working together.

---

## Slide 24

### Real-World Examples

Ask students to identify which protocols are involved in each activity.

| Activity | Likely Protocols |
|----------|------------------|
| Visiting a website | DNS, IP, TCP, HTTPS |
| Watching a video | DNS, IP, TCP, HTTPS |
| Reading email | DNS, TCP, SMTP, IMAP/POP3 |
| Online shopping | DNS, TCP, HTTPS |
| Cloud storage | DNS, TCP, HTTPS |

Students are **not** expected to memorise every protocol beyond those introduced in this lesson.

The objective is to recognise that multiple protocols cooperate.

---

## Slides 25–27

### Lesson Review

Invite students to summarise the lesson without reading their notes.

Suggested prompts:

- What is a protocol?
- Why is TCP important?
- What does IP do?
- Why is HTTPS safer than HTTP?
- Why do computers divide data into packets?

Encourage complete sentences rather than one-word answers.

---

# Assessment Guidance

## Workbook

Look for conceptual understanding rather than memorised wording.

Students should correctly explain:

- the purpose of protocols
- TCP vs IP
- HTTP vs HTTPS
- acknowledgements
- the overall communication process

---

## Quiz Expectations

Students should be able to:

✓ define a protocol

✓ explain TCP

✓ explain IP

✓ identify HTTPS

✓ describe packet acknowledgements

✓ explain why several protocols work together

---

# Suggested Marking Rubric

| Level | Description |
|------|-------------|
| Excellent | Explains concepts accurately using appropriate vocabulary and examples. |
| Proficient | Demonstrates clear understanding with only minor errors. |
| Developing | Understands some ideas but confuses several protocol roles. |
| Beginning | Requires additional support to explain basic concepts. |

---

# Differentiation

## Students Needing Support

- Use simplified protocol diagrams.
- Review Lesson 2 before introducing TCP/IP.
- Pair students strategically.
- Allow additional discussion time before independent tasks.
- Encourage students to explain ideas verbally before writing.

---

## Extension Opportunities

Students who finish early may investigate additional Internet protocols such as:

- FTP
- SSH
- SMTP
- IMAP
- POP3

Possible task:

Create a table describing the purpose of each protocol and identify a real-world situation where it is used.

---

# Cross-Curricular Connections

## Mathematics

- sequencing
- logical reasoning
- pattern recognition

## English

- technical vocabulary
- reading informational texts
- explaining processes clearly

## Science

- systems
- communication
- reliability

## Digital Citizenship

Discuss why secure communication is important when:

- shopping online
- logging into school systems
- sharing personal information
- using public Wi-Fi

---

# Homework Suggestions

Choose one of the following.

### Option A

Draw a flowchart showing what happens when you visit a website.

Include:

- URL
- DNS
- IP
- TCP
- HTTP/HTTPS
- Browser

---

### Option B

Write a short explanation (150–200 words):

**Why are network protocols important?**

Students should include at least three protocols discussed in class.

---

### Option C

Research one additional Internet protocol and prepare a one-minute presentation explaining:

- what it does
- where it is used
- why it is useful

---

# Reflection Questions

After the lesson, consider:

- Which concepts did students understand quickly?
- Which protocol caused the most confusion?
- Did students distinguish clearly between TCP and IP?
- Were students able to explain HTTPS without simply saying "it is safer"?
- Which activities generated the most discussion?

Use these reflections to adjust pacing for future classes.

---

# Teacher Reflection Log

## What Worked Well

____________________________________________________

____________________________________________________

____________________________________________________

---

## Challenges

____________________________________________________

____________________________________________________

____________________________________________________

---

## Students Requiring Follow-up

____________________________________________________

____________________________________________________

____________________________________________________

---

## Notes for Next Year

____________________________________________________

____________________________________________________

____________________________________________________

---

# Lesson Summary

By the end of Lesson 3, students should understand that:

- A protocol is a shared set of communication rules.
- Different protocols have different responsibilities.
- IP identifies destinations.
- TCP ensures reliable communication.
- HTTP transfers webpages.
- HTTPS encrypts web communication.
- ACKs confirm successful packet delivery.
- Modern Internet communication depends on many protocols working together.

This lesson provides the conceptual foundation for **Lesson 4 – Cybersecurity Fundamentals**, where students will apply their understanding of protocols to topics such as encryption, authentication, phishing, malware, and safe online behaviour.
Address misconceptions before continuing to the next section.

