# Grade 9 Digital Technology
# Unit 3 – Networks and the Internet
## Lesson 2 – How Does the Internet Work?

---

# Learning Intentions

In this lesson, you will learn:

- how computers communicate across the Internet.
- the difference between a client and a server.
- why every device needs an IP address.
- why humans use domain names instead of numbers.
- how the Domain Name System (DNS) works.
- the journey of a webpage from a web server to your browser.

---

# Success Criteria

By the end of this lesson, I can:

☐ explain the client–server model.

☐ identify the purpose of an IP address.

☐ explain why DNS is important.

☐ describe the steps that occur when loading a webpage.

☐ use networking vocabulary correctly.

---

# Starter Activity

## Think About It

Imagine you type the following address into your web browser.

```
www.wikipedia.org
```

Within a second, the webpage appears.

Have you ever wondered what happens during that short time?

Discuss the following questions with a partner.

1. How does your computer know where Wikipedia is?
2. How does the webpage travel to your computer?
3. Why does it happen so quickly?

Write down your ideas.

________________________________________________________

________________________________________________________

________________________________________________________

Remember:

There are no wrong answers at this stage.
Today's lesson will help you discover what really happens.

---

# Prior Knowledge Check

Before continuing, answer these questions.

| Question | Yes | Not Yet |
|-----------|:---:|:------:|
| I know what a computer network is. | □ | □ |
| I know what a LAN is. | □ | □ |
| I know the job of a router. | □ | □ |
| I know what the Internet is. | □ | □ |

If you answered "Not Yet" to any question, review Lesson 1 before continuing.

---

# Lesson Overview

Every day you:

- search Google
- watch YouTube
- send messages
- play online games
- submit homework

Although these tasks seem simple, they require thousands of computers around the world to communicate with each other.

The Internet is not a single computer.

Instead, it is a massive network made up of millions of connected devices.

Every webpage, photograph, video, email and online game relies on computers sending information to one another.

To understand how this works, we first need to learn about **clients** and **servers**.

---

# Clients and Servers

Imagine walking into a restaurant.

You ask for food.

The kitchen prepares the meal.

Finally, the waiter brings the food to your table.

A computer network works in a similar way.

One computer asks for information.

Another computer provides the information.

These two roles are called the **client** and the **server**.

---

## What Is a Client?

A client is a device that requests information or services.

Examples include:

- desktop computers
- laptops
- smartphones
- tablets
- smart TVs
- game consoles

Whenever you open a webpage or watch a video, your device is acting as a client.

---

## What Is a Server?

A server is a computer that provides information or services to clients.

Servers are usually much more powerful than personal computers because they may serve thousands or even millions of users at the same time.

Examples include:

- school learning management systems
- Google Drive
- Microsoft OneDrive
- YouTube
- Netflix
- online game servers

---

## Client or Server?

Decide whether each device is acting as a client or a server.

| Situation | Client | Server |
|-----------|:------:|:------:|
| Watching YouTube on a phone | □ | □ |
| Opening a school website | □ | □ |
| Printing a document through the school print server | □ | □ |
| Downloading homework from Google Classroom | □ | □ |

---

# The Client–Server Model

The client–server model describes how computers communicate across a network.

The process is simple.

Step 1

The client sends a **request**.

Step 2

The server receives the request.

Step 3

The server processes the request.

Step 4

The server sends a **response**.

Step 5

The client displays the result.

---

> **Insert Figure:** `docs/assets/images/grade9/unit3/client-server.svg`

*Figure 2.1. The client–server model. A client requests information, and a server responds.*

---

## Example

Suppose you visit:

```
www.bbc.com
```

Your laptop sends a request asking for the BBC homepage.

The BBC web server receives the request, finds the webpage files, and sends them back across the Internet.

Your browser receives the response and displays the webpage.

This entire process usually takes less than one second.

---

# Activity 1 – Acting It Out

Work in groups of three.

Assign the following roles:

- Student A: Client
- Student B: Server
- Student C: Network

Use a sheet of paper as the "request."

1. The client writes a request.
2. The network carries the request.
3. The server writes a response.
4. The network delivers the response.
5. The client reads the response.

After the activity, discuss:

- Which role was responsible for asking for information?
- Which role stored the information?
- Why is the network important?

---

# Check Your Understanding

Answer the following questions.

1. What is the main role of a client?

____________________________________________________

2. What is the main role of a server?

____________________________________________________

3. What is the difference between a request and a response?

____________________________________________________

4. Give one example of a client that you use every day.

____________________________________________________

---

# Did You Know?

Some of the world's largest companies operate millions of servers.

These servers are located in data centres around the world and work together to provide websites, cloud storage, online games and streaming services to billions of users every day.

This is why popular websites remain available even when millions of people visit them at the same time.

---

# Key Vocabulary

| Word | Definition |
|------|------------|
| Client | A device that requests information. |
| Server | A computer that provides information or services. |
| Request | A message asking for information. |
| Response | Information returned by a server. |
| Client–Server Model | A way computers communicate by requesting and providing services. |

---

## Coming Next

Now that you understand how computers communicate, the next question is:

**How does the Internet know which computer should receive the information?**

To answer that, we need to learn about **IP addresses**.
---

# IP Addresses – Every Device Needs an Address

Imagine that your friend wants to send you a birthday card.

If the envelope has no address, the post office will not know where to deliver it.

The Internet works in a similar way.

Every device connected to a network must have an address so that data knows where to go.

This address is called an **Internet Protocol (IP) address**.

An IP address is a unique numerical identifier assigned to a device on a network.

Without IP addresses, computers would not know where to send or receive information.

> **Insert Figure:** `docs/assets/images/grade9/unit3/ip-address.svg`

*Figure 2.2. Every device on a network requires a unique IP address.*

---

## An Example of an IPv4 Address

An IPv4 address consists of four numbers separated by periods.

```
192.168.1.15
```

Each number ranges from **0 to 255**.

Examples include:

```
10.0.0.25

172.16.5.100

203.15.88.9
```

These numbers may not be easy for people to remember, but computers can process them quickly.

---

## Public and Private IP Addresses

Not every IP address is visible on the Internet.

There are two common types.

### Public IP Address

A public IP address is visible on the Internet.

It allows your home or school network to communicate with websites and online services around the world.

Your Internet Service Provider (ISP) usually assigns this address.

### Private IP Address

A private IP address is used only inside a local network.

Examples include devices connected to your home Wi-Fi or your school's network.

Private IP addresses cannot normally be accessed directly from the Internet.

---

### Check Your Understanding

Which type of IP address is most likely used by the following?

| Device | Public | Private |
|---------|:------:|:-------:|
| Your laptop at school | □ | □ |
| Your home router | □ | □ |
| A classroom printer | □ | □ |
| A school desktop computer | □ | □ |

Discuss your answers with a partner.

---

# IPv4 and IPv6

When the Internet was first developed, engineers believed there would be enough IPv4 addresses for everyone.

Today, billions of devices are connected to the Internet.

This includes:

- computers
- smartphones
- tablets
- smart watches
- smart TVs
- game consoles
- security cameras
- Internet of Things (IoT) devices

Because so many devices now require addresses, a newer system was introduced.

This system is called **IPv6**.

---

## Comparing IPv4 and IPv6

| IPv4 | IPv6 |
|------|------|
| Older system | Newer system |
| Four groups of numbers | Eight groups of hexadecimal values |
| About 4.3 billion addresses | An extremely large number of addresses |
| Still widely used | Increasingly common |

You do **not** need to memorise IPv6 addresses.

Instead, remember **why** IPv6 was developed.

It provides enough addresses for the future growth of the Internet.

---

### Did You Know?

If every person on Earth owned several Internet-connected devices, IPv4 would not provide enough unique addresses.

IPv6 was designed to solve this problem.

---

# Domain Names

Imagine trying to remember the following number.

```
142.250.190.78
```

Most people would quickly forget it.

Now compare it with:

```
www.google.com
```

Which one is easier to remember?

Most people prefer names instead of numbers.

A **domain name** is a human-readable name that represents an IP address.

Some examples include:

- www.google.com
- www.wikipedia.org
- www.bbc.com
- www.openai.com

When you type a domain name into your browser, your computer still needs the IP address.

Something must translate the name into the correct number.

That is the job of **DNS**.

---

> **Insert Figure:** `docs/assets/images/grade9/unit3/url-breakdown.svg`

*Figure 2.3. A web address contains several parts that help identify a website.*

---

# The Domain Name System (DNS)

DNS stands for **Domain Name System**.

DNS is often described as the **phone book of the Internet**.

Imagine that you want to call a friend.

You probably search for their name in your contacts instead of memorising their phone number.

DNS performs a similar task.

It looks up the IP address that matches a domain name.

---

## How DNS Works

Suppose you type:

```
www.wikipedia.org
```

The following steps occur.

1. Your browser sends a request.
2. The request reaches a DNS server.
3. The DNS server finds the correct IP address.
4. The IP address is returned to your browser.
5. Your browser contacts the correct web server.

All of this usually happens in less than a second.

---

> **Insert Figure:** `docs/assets/images/grade9/unit3/dns-process.svg`

*Figure 2.4. DNS translates domain names into IP addresses before communication begins.*

---

# Worked Example

Let's follow the journey of a website request.

### Step 1

You type:

```
www.nasa.gov
```

### Step 2

Your browser asks a DNS server:

> "What is the IP address for www.nasa.gov?"

### Step 3

The DNS server returns the correct IP address.

### Step 4

Your browser sends a request to NASA's web server.

### Step 5

The server sends the webpage back to your computer.

### Step 6

Your browser displays the webpage.

Although this process involves multiple computers around the world, it normally takes less than a second.

---

# Activity 2 – Matching Terms

Match each term to its correct definition.

| Term | Definition |
|------|------------|
| Client | □ A unique numerical address |
| Server | □ Converts domain names into IP addresses |
| IP Address | □ Requests information |
| Domain Name | □ Provides information |
| DNS | □ Human-readable website name |

---

# Think Like a Network Engineer

Imagine that DNS suddenly stopped working worldwide.

Discuss the following questions.

- Could you still use website names?
- Would websites disappear?
- How would Internet users be affected?

Write two possible consequences below.

1. ___________________________________________

2. ___________________________________________

---

# Key Ideas So Far

You should now understand that:

- every device requires an IP address.
- domain names are easier for humans to remember than numbers.
- DNS translates names into IP addresses.
- clients communicate with servers using IP addresses.
- the Internet depends on many systems working together.

---

## Coming Next

You now know **how computers find one another**.

The next question is:

**How does an entire webpage travel across the Internet and appear in your browser?**
---

# How a Web Page Loads

When you open a website, many different systems work together to display the page on your screen.

Although this process seems almost instant, several important steps happen behind the scenes.

Understanding these steps helps us understand how the Internet works.

---

## Step 1 – Enter a URL

The process begins when you type a web address, also called a **URL (Uniform Resource Locator)**, into your browser.

For example:

```
https://www.wikipedia.org
```

The browser first checks whether it already knows the IP address of the website. If it does not, it asks a DNS server for help.

---

## Step 2 – DNS Finds the IP Address

The DNS server searches its records and returns the correct IP address.

Your browser now knows exactly which web server it needs to contact.

Without DNS, you would need to type long numerical IP addresses instead of easy-to-remember website names.

---

## Step 3 – The Browser Sends a Request

The browser sends a request across the Internet to the web server.

This request asks for the webpage and any resources needed to display it, such as images, style sheets and scripts.

---

## Step 4 – The Server Responds

The web server processes the request.

It locates the required files and sends them back to your browser.

This response may include:

- HTML files
- CSS files
- JavaScript files
- Images
- Videos
- Fonts

---

## Step 5 – The Browser Builds the Page

Your browser receives the files and combines them to create the webpage you see.

Although these steps involve many computers and networks around the world, they usually take less than one second.

---

> **Insert Figure:** `docs/assets/images/grade9/unit3/how-web-page-loads.svg`

*Figure 2.5. The journey of a webpage from the browser to the server and back again.*

---

# Data Travels in Packets

Earlier, you learned that networks send information using **packets**.

A packet is a small piece of data.

Instead of sending one very large file all at once, the file is divided into many smaller packets.

Each packet may travel along a different route through the Internet.

When the packets arrive at your computer, they are placed back into the correct order.

This process is usually so fast that users never notice it happening.

---

> **Insert Figure:** `docs/assets/images/grade9/unit3/packet-transmission.svg`

*Figure 2.6. Data is divided into packets before travelling across the network.*

---

## Why Use Packets?

Sending information as packets has several advantages.

- Packets can take different routes if one path is busy.
- Lost packets can be sent again without resending the entire file.
- Many users can share the same network efficiently.
- Large files can be transferred more reliably.

---

# Case Study – Opening a School Learning Portal

Imagine that you want to access your school's Learning Management System (LMS).

The following events take place.

1. You enter the school's website address.
2. DNS finds the correct IP address.
3. Your browser sends a request.
4. The school server receives the request.
5. The server checks your login details.
6. The server sends your dashboard and course information.
7. Your browser displays the webpage.

This entire process normally happens in just a few seconds.

---

# Activity 3 – Sequence the Process

Number the following steps from **1** to **6**.

| Step | Order |
|------|:----:|
| Browser displays the webpage. | □ |
| DNS returns the IP address. | □ |
| User enters a URL. | □ |
| Browser contacts the web server. | □ |
| Server sends webpage files. | □ |
| Browser asks DNS for the IP address. | □ |

---

# Activity 4 – Applying Your Knowledge

Complete the table.

| Situation | Client | Server | DNS Needed? |
|-----------|--------|--------|:-----------:|
| Watching an online video | | | |
| Reading a news website | | | |
| Accessing the school LMS | | | |
| Using cloud storage | | | |

Discuss your answers with a partner.

---

# Challenge Activity

A student says:

> "The Internet is just one giant computer."

Explain why this statement is incorrect.

Use the following words in your explanation.

- client
- server
- network
- IP address
- DNS

Write your response below.

____________________________________________________

____________________________________________________

____________________________________________________

____________________________________________________

---

# Common Misconceptions

### Misconception 1

**"The Internet stores my files."**

Not exactly.

Your files are stored on servers connected to the Internet.

---

### Misconception 2

**"Google is the Internet."**

Google is a company that provides services on the Internet.

The Internet is the global network that connects millions of computers.

---

### Misconception 3

**"DNS stores websites."**

DNS does not store webpages.

It stores information that helps computers find the correct server.

---

### Misconception 4

**"A server is always a huge machine."**

Many servers are powerful computers in data centres, but a server is defined by its role—providing services—not by its physical size.

---

# Summary

In this lesson you learned that:

- The Internet is a network of connected computers.
- A **client** requests information.
- A **server** provides information.
- Every device needs an **IP address**.
- **Domain names** make websites easier for people to remember.
- **DNS** converts domain names into IP addresses.
- Webpages are delivered through requests, responses and data packets.

---

# Vocabulary Review

| Word | Meaning |
|------|---------|
| Client | A device that requests information or services. |
| Server | A computer that provides information or services. |
| IP Address | A unique numerical address for a device on a network. |
| Domain Name | A human-readable website address. |
| DNS | The system that translates domain names into IP addresses. |
| URL | The address of a webpage or online resource. |
| Packet | A small piece of data sent across a network. |
| Request | A message asking for information. |
| Response | Information returned by a server. |

---

# Reflection

Complete the following sentences.

Today I learned that...

____________________________________________________

____________________________________________________

The most interesting idea was...

____________________________________________________

____________________________________________________

The concept I found most challenging was...

____________________________________________________

____________________________________________________

One question I still have is...

____________________________________________________

____________________________________________________

---

# Exit Ticket

Answer these questions without using your notes.

1. What is the purpose of an IP address?

____________________________________________________

2. Why do we use domain names instead of IP addresses?

____________________________________________________

3. What is the role of DNS?

____________________________________________________

4. Explain the difference between a client and a server.

____________________________________________________

____________________________________________________

5. Describe the journey of a webpage from the moment you type a URL until it appears in your browser.

____________________________________________________

____________________________________________________

____________________________________________________

____________________________________________________

---

# Extension Challenge

Research one technology that makes the modern Internet faster or more reliable.

Choose one of the following topics:

- Content Delivery Network (CDN)
- Fibre-optic Internet
- 5G Networks
- Cloud Computing
- Edge Computing

Create a one-page summary that includes:

- What it is
- How it works
- Why it is important
- One real-world example

Be prepared to present your findings in the next lesson.

---

# Looking Ahead

In **Lesson 3**, you will explore how information moves across networks using **network protocols**.

You will learn about concepts such as:

- TCP and UDP
- Reliability and speed
- Error checking
- Real-world communication protocols

These technologies make it possible for billions of devices to communicate accurately every day.
