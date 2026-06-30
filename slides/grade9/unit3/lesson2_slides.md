
# Grade 9 Digital Technology
# Unit 3 – Networks and the Internet
## Lesson 2 – How Does the Internet Work?

---

# Slide 1 – Title

## How Does the Internet Work?

**Unit 3 – Networks and the Internet**

Grade 9 Digital Technology

---

### Speaker Notes

Welcome students.

Today we will answer a question that most people never think about:

> "What actually happens after you press Enter in your web browser?"

By the end of today's lesson, you'll understand the journey from typing a website address to seeing the webpage appear.

---

# Slide 2 – Learning Intentions

## Today We Will Learn

✔ The client–server model

✔ What an IP address is

✔ Why domain names exist

✔ The purpose of DNS

✔ How a webpage loads

---

### Speaker Notes

Explain that these ideas are connected.

Each concept helps solve one problem in Internet communication.

Encourage students to think about how these pieces fit together.

---

# Slide 3 – Starter Question

## Think!

When you type:

```
www.wikipedia.org
```

What happens before the webpage appears?

Take one minute to think.

Then discuss with a partner.

---

### Speaker Notes

Do not confirm answers immediately.

Accept all reasonable ideas.

Record student responses on the board.

Examples:

- Wi-Fi downloads it.
- Google finds it.
- The browser searches.
- Another computer sends it.

Tell students they will discover which ideas are correct.

---

# Slide 4 – Lesson Roadmap

## Today's Journey

```
Client

↓

Server

↓

IP Address

↓

Domain Name

↓

DNS

↓

Webpage Loading
```

---

### Speaker Notes

Show students that today's lesson is a journey.

Each concept builds on the previous one.

Avoid explaining everything now.

Simply introduce the roadmap.

---

# Slide 5 – Client and Server

## Two Different Roles

### Client

Requests information

Examples

- Laptop
- Phone
- Tablet
- Chromebook

---

### Server

Provides information

Examples

- Google
- YouTube
- Netflix
- School LMS

---

### Speaker Notes

Emphasise:

A client and server describe **roles**, not special types of computers.

The same computer can perform different roles in different situations.

---

# Slide 6 – Real-Life Analogy

## Restaurant Analogy

Customer

↓

Places an order

↓

Kitchen

↓

Prepares food

↓

Customer receives food

---

### Internet Version

Client

↓

Request

↓

Server

↓

Response

↓

Client

---

### Speaker Notes

Walk through the analogy slowly.

Ask:

"Who asks for food?"

(Customer)

"Who prepares the food?"

(Kitchen)

Relate this to:

Client → Request

Server → Response

---

# Slide 7 – Quick Discussion

## Which Is the Client?

Scenario 1

You watch a YouTube video.

Client?

Server?

---

Scenario 2

You open Google Classroom.

Client?

Server?

---

Scenario 3

You search on Google.

Client?

Server?

---

### Speaker Notes

Invite students to answer verbally.

Expected responses:

Client → Student device

Server → Online service

Reinforce the idea that servers provide resources.

---

# Slide 8 – Common Misconceptions

## Myth or Fact?

❓ "Google is the Internet."

❓ "The Internet is one giant computer."

❓ "My laptop stores every website."

Think...

Which statements are incorrect?

---

### Speaker Notes

Reveal the answers one at a time.

Explain:

- Google is a service on the Internet.
- The Internet is a network of millions of computers.
- Websites are stored on web servers.

Encourage students to explain *why* each statement is incorrect.

---

# Slide 9 – Transition

## New Question

If every website is stored on another computer...

How does your computer know **which computer** to contact?

🤔

---

### Speaker Notes

Pause for student ideas.

Do not answer immediately.

Tell students:

"To solve this problem, computers use something called an **IP address**."

---

# Slide 10 – What Is an IP Address?

## Every Device Needs an Address

Just as every house has an address...

🏠 **House Address** → Mail Delivery

💻 **IP Address** → Data Delivery

### Example

```
192.168.1.15
```

---

### Speaker Notes

Begin with the house-address analogy.

Ask:

> "Could a letter reach your house without an address?"

Guide students to see that computers also need unique addresses so data can be delivered to the correct destination.

Avoid discussing binary numbers or networking standards.

---

# Slide 11 – IPv4 and IPv6

## Why Are There Two Versions?

### IPv4

```
192.168.1.15
```

- Older system
- Four groups of numbers
- Limited number of addresses

---

### IPv6

```
2001:0db8:85a3::8a2e:0370:7334
```

- Newer system
- Much larger address space
- Supports billions of additional devices

---

### Speaker Notes

Students do **not** need to memorise IPv6.

Emphasise **why** IPv6 exists:

- more phones
- more tablets
- smart TVs
- watches
- cars
- IoT devices

---

# Slide 12 – Why Do We Use Domain Names?

## Which Is Easier to Remember?

### Option A

```
142.250.190.78
```

### Option B

```
www.google.com
```

**Which would you rather remember?**

---

### Speaker Notes

Give students 10 seconds to memorise the IP address.

Hide it.

Repeat with the domain name.

Most students will remember the domain name more easily.

Conclude:

> Humans prefer names.
>
> Computers use numbers.

---

# Slide 13 – What Is DNS?

## DNS = Domain Name System

DNS translates

```
www.google.com
```

⬇

```
142.250.190.78
```

Think of DNS as:

📖 **The Internet's Address Book**

---

### Speaker Notes

Avoid saying only "phone book."

Explain that an address book or contacts list is a more familiar example for many students.

Reinforce:

- Humans remember names.
- Computers communicate using IP addresses.
- DNS connects the two.

---

# Slide 14 – How DNS Works

*(Display: `dns-process.svg`)*

## DNS Process

1. User enters a website name.
2. Browser asks DNS.
3. DNS returns the IP address.
4. Browser contacts the web server.

---

### Speaker Notes

Walk through each step slowly.

Point to the diagram as you explain.

Ask after each step:

> "What happens next?"

Encourage students to narrate the process rather than simply read it.

---

# Slide 15 – Mini Activity

## Match the Pairs

| Item | Match |
|------|-------|
| Domain Name | ? |
| IP Address | ? |
| DNS | ? |

Choose from:

- Human-readable name
- Numerical address
- Translation service

---

### Speaker Notes

Allow students to answer individually for one minute.

Then compare answers with a partner before discussing as a class.

Expected matches:

- Domain Name → Human-readable name
- IP Address → Numerical address
- DNS → Translation service

---

# Slide 16 – Check Your Understanding

### True or False?

1. DNS stores every website.

2. Computers communicate using IP addresses.

3. Domain names are easier for people to remember.

4. A client provides information to a server.

---

### Speaker Notes

Review answers together.

Correct responses:

1. False
2. True
3. True
4. False

Use incorrect answers as opportunities to revisit misconceptions.

---

# Slide 17 – Think, Pair, Share

## Discuss

Imagine DNS stopped working for one day.

What problems would people experience?

Talk with your partner for two minutes.

---

### Speaker Notes

Possible student responses:

- Websites would not load using names.
- People would need to know IP addresses.
- Online services would become difficult to access.

Accept creative answers if students justify their reasoning.

Highlight that DNS is a critical part of the Internet but is usually invisible to users.

---

# Slide 18 – Transition

## One Final Question

Now we know **how the browser finds the correct server**...

But what happens **after** the server is found?

➡️ How does the webpage travel back to your computer?

---

### Speaker Notes

Do not answer yet.

Tell students that the final section follows the complete journey of a webpage—from entering a URL to seeing the page on the screen.

Transition to the webpage loading sequence.


This creates a natural transition into the next section of the lesson.

---

# Slide 19 – How Does a Webpage Load?

*(Display: `how-web-page-loads.svg`)*

## From URL to Webpage

```
Type URL

↓

DNS finds IP Address

↓

Browser sends Request

↓

Web Server responds

↓

Browser displays Webpage
```

---

### Speaker Notes

This is the most important diagram of today's lesson.

Walk through each step slowly.

Ask students to explain each stage in their own words.

Reinforce that the entire process usually takes less than a second.

---

# Slide 20 – Following the Journey

## Can You Explain the Process?

Imagine opening:

```
www.wikipedia.org
```

Work with a partner.

Can you describe every step?

Use these words:

- Browser
- DNS
- IP Address
- Server
- Request
- Response

---

### Speaker Notes

Give students two minutes.

Walk around the classroom and listen to explanations.

Encourage students to use complete sentences rather than isolated vocabulary.

Invite one or two pairs to explain the process to the class.

---

# Slide 21 – Packets in Action

*(Display: `packet-transmission.svg`)*

## How Does Large Information Travel?

Large files are divided into:

📦 **Packets**

Packets may:

- travel different routes
- arrive at different times
- be reassembled correctly

---

### Speaker Notes

Remind students of Lesson 1.

Explain that sending one huge file would be inefficient.

Using packets makes communication faster, more reliable and easier to manage.

You do not need to introduce TCP/IP in detail yet—that will come in the next lesson.

---

# Slide 22 – Everyday Examples

## Where Have You Used This Today?

Think about the websites or apps you used before school.

Examples:

- YouTube
- Google Classroom
- Netflix
- Spotify
- Instagram
- BBC News

Question:

**Did they all use the same basic process?**

✅ Yes!

---

### Speaker Notes

Help students connect today's concepts to their daily lives.

Regardless of the website or app, the fundamental process remains the same:

- Client
- DNS
- IP Address
- Server
- Response

---

# Slide 23 – Review

## Complete the Sentences

1.

A **client** ___________________________

---

2.

A **server** ___________________________

---

3.

DNS translates

____________________

into

____________________

---

4.

An IP address is

____________________________

---

### Speaker Notes

Ask students to answer verbally or write responses in their notebooks.

Suggested answers:

- requests information
- provides information
- domain names → IP addresses
- a unique address used to identify a device on a network

---

# Slide 24 – Exit Ticket

Before you leave, answer these questions.

1. What is one new thing you learned today?

2. Why is DNS important?

3. What question do you still have?

---

### Speaker Notes

Collect responses as students leave or use an online form.

These answers provide valuable formative assessment and identify misconceptions to revisit.

---

# Slide 25 – Homework

Choose ONE activity.

### Option A

Draw a flowchart showing how a webpage loads.

---

### Option B

Explain the Internet process to a family member using your own words.

---

### Option C

Research one topic:

- Cloud Computing
- Data Centres
- Content Delivery Networks (CDNs)

Prepare a short summary for the next lesson.

---

### Speaker Notes

Encourage students to use diagrams rather than copying definitions.

For extension students, Option C provides a useful bridge to future networking topics.

---

# Slide 26 – Looking Ahead

## Next Lesson

### Network Protocols

How do billions of computers communicate using the same rules?

Topics include:

- Communication protocols
- TCP/IP (Introduction)
- Reliable data transmission
- Why standards matter

---

### Speaker Notes

Conclude by explaining that today students learned **where** information goes.

Next lesson, they will learn **how** computers agree on the rules for sending and receiving information.

This creates a natural progression into Lesson 3.

---

# Final Slide – Key Takeaways

## Today You Learned...

✅ The difference between a client and a server

✅ Why every device needs an IP address

✅ Why humans use domain names

✅ How DNS translates names into addresses

✅ The complete journey of a webpage

---

### Remember

> **People use names.**

> **Computers use numbers.**

> **DNS connects the two.**

> **The Internet works because millions of devices follow the same process.**

---

### Speaker Notes

Finish with a brief recap.

Ask students to rate their confidence (1–5 fingers or thumbs up/down).

Invite one volunteer to explain the entire webpage loading process without looking at their notes.

Congratulate the class on completing Lesson 2 and preview the exciting concepts in Lesson 3.
