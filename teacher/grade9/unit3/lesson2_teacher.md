# Grade 9 Digital Technology
# Teacher Guide
# Unit 3 – Networks and the Internet
## Lesson 2 – How Does the Internet Work?

---

# Lesson Information

**Year Level:** Grade 9

**Recommended Duration:** 70–80 minutes

**Curriculum Strand:** Networks and Internet Technologies

**Prerequisite Knowledge**

Students should already understand:

- what a computer network is
- the difference between LAN and WAN
- the purpose of routers and switches
- that information travels in packets

(Refer to Unit 3 Lesson 1 if necessary.)

---

# Lesson Overview

This lesson introduces students to one of the most important ideas in networking:

**How information travels across the Internet.**

Students learn that communication on the Internet follows a client–server model.

They investigate:

- clients
- servers
- IP addresses
- domain names
- DNS
- webpage loading

Rather than memorising technical definitions, students are encouraged to understand the sequence of events that occurs whenever they open a webpage.

This lesson provides the conceptual foundation for later lessons on protocols, cybersecurity and cloud computing.

---

# Learning Intentions

Students will:

- explain how clients and servers communicate
- describe the purpose of IP addresses
- explain why domain names are used
- describe the role of DNS
- explain the process of loading a webpage

---

# Success Criteria

Students can:

☐ explain the client–server model

☐ identify examples of clients and servers

☐ explain why every device requires an IP address

☐ describe the purpose of DNS

☐ sequence the steps involved in loading a webpage

---

# Resources

Required

- Student Book (Lesson 2)
- Projector or interactive display
- Internet connection
- Whiteboard
- Student notebooks

Recommended

- `client-server.svg`
- `dns-process.svg`
- `how-web-page-loads.svg`
- `url-breakdown.svg`
- `ip-address.svg`

Optional

- Teacher laptop
- School website
- Google Classroom
- Live demonstration of a webpage loading

---

# Lesson Sequence

| Stage | Time |
|---------|------|
| Starter | 10 min |
| Direct Instruction | 20 min |
| Guided Practice | 20 min |
| Independent Activity | 20 min |
| Reflection | 10 min |

---

# Starter (10 minutes)

Display the following question.

> "What happens after you press Enter when visiting a website?"

Allow students one minute to think individually.

Students then discuss with a partner.

Finally, invite several students to share their ideas.

---

## Expected Responses

Students may say:

- The Internet finds the website.
- Google opens the webpage.
- Wi-Fi downloads it.
- The browser searches online.
- The computer contacts another computer.

Do not immediately correct incorrect answers.

Record ideas on the board.

Explain that today's lesson will investigate which ideas are correct.

---

# Activating Prior Knowledge

Ask the class:

1. What is a network?

2. What is a router?

3. What is the Internet?

4. What does a website need before it can appear on your screen?

Students should connect today's lesson with concepts learned in Lesson 1.

If necessary, briefly review:

- LAN
- WAN
- Routers
- Data packets

Limit this review to five minutes.

---

# Direct Instruction

## Introducing Clients and Servers

Display:

`client-server.svg`

Begin with a familiar example.

Teacher:

> "When you order food at a restaurant, who asks for the food?"

Students:

"The customer."

Teacher:

> "Who prepares the food?"

Students:

"The kitchen."

Explain:

The customer behaves like a client.

The kitchen behaves like a server.

The waiter is similar to the network carrying information between them.

This analogy helps students understand the client–server model before introducing technical terminology.

---

# Teaching Notes

Emphasise:

A server is **not** simply a powerful computer.

A server is defined by the service it provides.

Any computer can become a server if it provides resources to other devices.

Avoid statements such as:

> "Servers are always very large."

Instead say:

> "Many servers are powerful because they serve many users, but their role is more important than their size."

---

# Guided Discussion

Ask students:

"What devices have you used today?"

List responses.

Possible answers:

- phone
- laptop
- tablet
- Chromebook

Then ask:

"When you watched YouTube this morning, was your phone acting as a client or a server?"

Expected answer:

Client.

Next ask:

"What computer provided the video?"

Expected answer:

YouTube server.

---

# Common Misconceptions

### Misconception

"The Internet is one giant computer."

Correction

Explain that the Internet is a network connecting millions of computers.

---

### Misconception

"Google is the Internet."

Correction

Explain that Google provides services on the Internet.

Students often confuse companies with the infrastructure itself.

---

### Misconception

"My laptop stores every website."

Correction

Websites remain on servers.

The browser only downloads the information needed to display the page.

---

# Transition

Conclude this section by asking:

"If computers can communicate with one another, how do they know exactly which computer to contact?"

Allow students to suggest ideas.

Do not introduce the answer yet.

Explain that the next section introduces **IP addresses**, which solve this problem.
---

# Teaching IP Addresses

## Learning Goal

Students understand that every device connected to a network requires a unique address.

Avoid beginning with technical definitions.

Instead, begin with a familiar situation.

---

## Teacher Demonstration

Hold up an envelope (or display an image of one).

Ask:

> "Could the post office deliver this letter if it had no address?"

Students should answer:

> "No."

Ask:

> "Why not?"

Guide students toward the idea that an address tells the delivery system where the letter should go.

Explain that the Internet has the same problem.

Data cannot be delivered unless every device has an address.

Introduce the term:

**IP Address**

Write on the board:

```
House Address
        ↓
Delivery

IP Address
        ↓
Data Delivery
```

Emphasise that an IP address is simply the network's way of identifying a device.

Avoid overwhelming students with binary numbers or networking standards.

The goal is conceptual understanding.

---

# Introducing IPv4

Display the example:

```
192.168.1.15
```

Ask students:

> "How many groups of numbers can you see?"

Expected answer:

Four.

Then ask:

> "Do you think people enjoy memorising numbers like this?"

Students usually answer:

"No."

Use this discussion to transition naturally to domain names.

---

# Teaching IPv6

Students do **not** need to memorise IPv6 addresses.

Instead, explain the reason IPv6 exists.

Suggested explanation:

> "When the Internet was first created, engineers believed there would be enough addresses for everyone. Today we have billions of devices including phones, tablets, watches, televisions and even refrigerators. IPv6 provides many more addresses for the future."

Avoid discussing hexadecimal notation unless students ask.

If students are curious, simply explain that IPv6 uses a different numbering system to create many more unique addresses.

---

# Teaching Domain Names

Display:

```
142.250.190.78
```

Ask students to look at the number for five seconds.

Hide the number.

Ask:

> "Who can remember it?"

Very few students will succeed.

Now display:

```
www.google.com
```

Hide it after five seconds.

Almost every student will remember it.

Use this simple activity to demonstrate why domain names exist.

Students quickly understand that names are easier for humans while numbers are easier for computers.

---

# Introducing DNS

Display:

`dns-process.svg`

Explain that DNS stands for **Domain Name System**.

Avoid giving only the acronym.

Students remember concepts more effectively when they understand the purpose.

Use the analogy below.

---

## Teacher Analogy

Ask:

> "Do you remember your best friend's phone number?"

Many students will answer "No."

Then ask:

> "How do you call them?"

Expected responses:

- Contacts
- Phone book
- Search

Explain:

DNS works in exactly the same way.

People remember names.

Computers use numbers.

DNS connects the two.

---

# Suggested Teacher Questions

Use open-ended questions whenever possible.

Instead of asking:

> "Is DNS important?"

Ask:

> "What problems would people face if DNS disappeared tomorrow?"

Possible student responses:

- We would have to remember numbers.
- Websites would be difficult to find.
- Browsing would become slower and more confusing.

These responses demonstrate conceptual understanding rather than memorisation.

---

# Mini Demonstration

Open a web browser.

Type:

```
www.wikipedia.org
```

Ask students:

"What happened before the page appeared?"

Guide discussion toward the hidden steps.

Students often assume the browser goes directly to the webpage.

Explain that several systems work together:

1. Browser
2. DNS
3. Web server
4. Response
5. Browser display

Point out that these steps happen automatically within fractions of a second.

---

# Formative Assessment Checkpoint

Before moving on, ask students to complete the following statements.

1.

A client is a computer that ___________________________

Expected response:

requests information.

---

2.

A server is a computer that ___________________________

Expected response:

provides information or services.

---

3.

An IP address is ___________________________

Expected response:

a unique address used to identify a device on a network.

---

4.

DNS is responsible for ___________________________

Expected response:

translating domain names into IP addresses.

---

# Differentiation

## Support

Provide students with a vocabulary card containing:

- Client
- Server
- IP Address
- Domain Name
- DNS

Include both definitions and simple diagrams.

Allow students to work with a partner during sequencing activities.

---

## Extension

Ask higher-achieving students:

> "Could two devices on the same network use exactly the same IP address?"

Encourage discussion.

Guide students toward the idea that duplicate addresses would cause communication problems because the network would not know which device should receive the data.

No detailed discussion of IP conflicts is required at this stage.

---

# Teacher Tips

Students often confuse these pairs of terms.

| Students Confuse | Clarification |
|------------------|---------------|
| Internet and Google | Google is a service on the Internet. |
| Website and Server | A server stores and delivers websites. |
| Domain Name and URL | A domain name is one part of a URL. |
| Wi-Fi and Internet | Wi-Fi connects a device to a local network; Internet access depends on additional network infrastructure. |

Return to these distinctions whenever they arise during discussion.

---

# Transition to the Final Section

Ask the class:

> "Now we know how a browser finds a server. What happens after the browser has found the correct server?"

Invite a few predictions.

Explain that the next section follows the complete journey of a webpage—from the moment a URL is entered until the webpage appears on the screen.
---

# Teaching "How a Web Page Loads"

## Learning Goal

Students understand that loading a webpage is a sequence of coordinated actions rather than a single event.

Students should recognise that several systems cooperate:

- Browser
- DNS
- Internet
- Web Server
- Data Packets

The emphasis is on the overall process, not memorising technical terminology.

---

## Teaching Sequence

Display:

`how-web-page-loads.svg`

Guide students through the process one step at a time.

### Step 1

The user types a URL.

Ask:

> "What is the first thing your browser knows?"

Expected response:

The website name.

---

### Step 2

DNS finds the IP address.

Ask:

> "Why can't the browser use only the website name?"

Expected response:

Computers communicate using IP addresses.

---

### Step 3

The browser sends a request.

Explain that requests are simply messages asking for information.

Avoid introducing HTTP methods such as GET and POST at this stage.

---

### Step 4

The server prepares the webpage.

Explain that the server collects the required files before sending them back.

---

### Step 5

The browser receives the files and builds the webpage.

Emphasise that the browser is responsible for displaying the page—not the server.

---

# Revisiting Packets

Display:

`packet-transmission.svg`

Remind students that this concept was introduced in Lesson 1.

Review the following points.

- Large files are divided into packets.
- Packets may travel along different routes.
- Missing packets can be resent.
- The receiving computer rebuilds the original file.

Do not spend more than five minutes reviewing this concept.

The goal is reinforcement rather than reteaching.

---

# Facilitating Activity 3

Students arrange the webpage loading process into the correct order.

## Correct Order

1. User enters a URL.
2. Browser asks DNS for the IP address.
3. DNS returns the IP address.
4. Browser contacts the web server.
5. Server sends webpage files.
6. Browser displays the webpage.

---

## Discussion Questions

Ask:

> "Which step would fail if DNS stopped working?"

Expected response:

The browser would not know the server's IP address.

---

Ask:

> "Would the server still exist?"

Expected response:

Yes.

Explain that DNS helps computers locate servers. It does not create or store them.

---

# Facilitating Activity 4

Students identify the client, server and whether DNS is involved.

## Suggested Answers

| Situation | Client | Server | DNS Needed? |
|-----------|--------|--------|:-----------:|
| Watching an online video | Student device | Video server | Yes |
| Reading a news website | Student device | News server | Yes |
| School LMS | Student device | LMS server | Yes |
| Cloud storage | Student device | Cloud server | Yes |

If students suggest that DNS is not always required because an IP address could be entered directly, acknowledge this as an excellent extension idea while explaining that, in normal everyday use, DNS is involved.

---

# Extension Discussion

Ask students:

> "Why do you think websites use names instead of long numbers?"

Encourage answers related to usability and human memory.

Then ask:

> "Why do computers still need numbers?"

Guide students toward the idea that numerical addressing allows accurate communication between devices.

---

# Exit Ticket Answer Guide

### Question 1

What is an IP address?

Expected answer:

A unique numerical address that identifies a device on a network.

---

### Question 2

Why do we use domain names?

Expected answer:

They are easier for people to remember than numerical IP addresses.

---

### Question 3

What is the role of DNS?

Expected answer:

DNS translates domain names into IP addresses.

---

### Question 4

Explain the difference between a client and a server.

Expected answer:

A client requests information, while a server provides information or services.

---

### Question 5

Describe how a webpage loads.

Students should include most of these steps:

- Enter URL
- DNS lookup
- Browser contacts server
- Server sends files
- Browser displays webpage

Minor wording differences are acceptable if the sequence is correct.

---

# Assessment Rubric

| Criteria | Beginning | Developing | Proficient | Advanced |
|----------|-----------|------------|------------|----------|
| Client–Server Model | Identifies few roles | Explains basic roles | Correctly explains communication | Applies concept to unfamiliar situations |
| IP Address | Limited understanding | Knows basic purpose | Explains why devices need addresses | Connects addressing to networking concepts |
| DNS | Limited understanding | Recognises its purpose | Correctly explains name-to-IP translation | Explains the complete lookup process |
| Webpage Loading | Lists isolated ideas | Describes some steps | Explains the correct sequence | Explains the process confidently using correct terminology |

---

# Homework

Students complete one of the following tasks.

### Option A

Create a flowchart showing how a webpage loads.

Include:

- URL
- DNS
- Browser
- Server
- Webpage

---

### Option B

Interview a family member.

Ask:

> "What do you think happens when you open a website?"

Compare their explanation with what you learned in class.

---

### Option C (Extension)

Research one of the following:

- DNS
- Cloud Computing
- Data Centres
- Content Delivery Networks (CDNs)

Prepare a short one-page summary including:

- Definition
- Purpose
- One real-world example

---

# Cross-Curricular Connections

### English

Students explain technical concepts using clear written language.

---

### Mathematics

Students recognise that computers use numerical addressing systems.

---

### Media Studies

Students investigate how online media is delivered through networks.

---

### Digital Citizenship

Students begin understanding the infrastructure that supports everyday online activities.

---

# Preparing Students for Lesson 3

Conclude the lesson by asking:

> "Finding the correct computer is only part of the problem."

Then ask:

> "How can billions of computers communicate in exactly the same way?"

Allow students to speculate.

Explain that the next lesson introduces **network protocols**, the shared rules that allow devices to communicate reliably.

---

# Teacher Reflection

After teaching, reflect on the following questions.

### Student Understanding

- Could students distinguish between clients and servers?
- Did students understand why DNS is necessary?
- Could students explain the webpage loading process in the correct order?

---

### Student Engagement

- Which activity generated the most discussion?
- Which examples were easiest for students to understand?
- Which misconceptions appeared most frequently?

---

### Future Improvements

Consider:

- spending more time on DNS if students found it difficult.
- using additional real-world demonstrations.
- revisiting packet transmission before Lesson 3 if required.

Record notes below.

____________________________________________________

____________________________________________________

____________________________________________________

____________________________________________________

---

# End of Lesson

Students should now understand:

✓ Client–Server Communication

✓ IP Addresses

✓ Domain Names

✓ DNS

✓ Webpage Loading

These concepts provide the foundation for **Lesson 3 – Network Protocols**, where students will explore how computers follow shared rules to exchange information accurately and efficiently.
