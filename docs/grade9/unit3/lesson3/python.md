# Grade 9 Digital Technology
# Python Lab
# Unit 3 – Networks and the Internet
## Lesson 2 – Simulating the Internet with Python

---

# Learning Objectives

By the end of this activity, you will be able to:

- understand how DNS works
- simulate a simple web request
- use Python dictionaries to store network information
- write functions to retrieve data
- explain how computers locate websites

---

# Introduction

When you type a website such as:

```
www.wikipedia.org
```

your computer cannot use that name directly.

Instead, it asks a **DNS server** for the website's IP address.

In this activity, you will build a simple DNS simulator using Python.

---

# Activity 1 – Your First DNS Database

A Python dictionary is perfect for storing website names and IP addresses.

```python
dns = {
    "www.google.com": "142.250.190.78",
    "www.wikipedia.org": "208.80.154.224",
    "www.openai.com": "104.18.33.45",
    "school.edu": "192.168.1.10"
}

print(dns)
```

### Questions

1. Which website has the IP address **208.80.154.224**?

________________________________________________

2. Which website uses **192.168.1.10**?

________________________________________________

---

# Activity 2 – Looking Up an IP Address

Python allows us to search a dictionary.

```python
dns = {
    "www.google.com": "142.250.190.78",
    "www.wikipedia.org": "208.80.154.224",
    "www.openai.com": "104.18.33.45"
}

website = input("Enter a website: ")

if website in dns:
    print("IP Address:", dns[website])
else:
    print("Website not found.")
```

### Try These

```
www.google.com
```

```
www.openai.com
```

```
www.school.edu
```

What happens if the website is not in the dictionary?

________________________________________________

________________________________________________

---

# Activity 3 – Add a New Website

Modify the dictionary.

Add your school's website.

Example:

```python
dns["www.myschool.edu"] = "203.12.45.18"
```

Print the dictionary again.

How many websites are stored?

_____________

---

# Activity 4 – Simulating a Browser

Create a function.

```python
dns = {
    "www.google.com": "142.250.190.78",
    "www.wikipedia.org": "208.80.154.224"
}

def visit(site):
    if site in dns:
        print("Looking up DNS...")
        print("IP Address:", dns[site])
        print("Connecting to server...")
        print("Downloading webpage...")
        print("Page loaded!")
    else:
        print("Website not found.")

visit("www.google.com")
```

---

## Output

```
Looking up DNS...

IP Address: 142.250.190.78

Connecting to server...

Downloading webpage...

Page loaded!
```

Discuss.

Which part represents DNS?

________________________________________________

Which part represents the server?

________________________________________________

---

# Activity 5 – Building a Mini Internet

Create a larger dictionary.

```python
dns = {
    "www.google.com":"142.250.190.78",
    "www.wikipedia.org":"208.80.154.224",
    "www.bbc.com":"151.101.0.81",
    "www.youtube.com":"142.250.191.78",
    "www.openai.com":"104.18.33.45"
}
```

Ask the user to enter a website.

Display:

- website name
- IP address
- "Connection successful"

---

# Challenge Activity

Instead of only displaying the IP address,

also display a webpage title.

Example:

```python
websites = {
    "www.google.com": {
        "ip":"142.250.190.78",
        "title":"Google Search"
    },

    "www.wikipedia.org": {
        "ip":"208.80.154.224",
        "title":"Wikipedia"
    }
}
```

Output

```
Website

www.wikipedia.org

IP Address

208.80.154.224

Title

Wikipedia
```

---

# Extension Challenge

Create a fake web browser menu.

```
======================

Mini Browser

======================

1. Visit Website

2. Show DNS Records

3. Exit
```

Use a **while loop** so the program continues until the user chooses Exit.

---

# Reflection

Answer the questions.

### 1.

How is a Python dictionary similar to DNS?

________________________________________________

________________________________________________

---

### 2.

Why are dictionaries useful for storing network information?

________________________________________________

________________________________________________

---

### 3.

Which Python concept was most useful today?

☐ Variables

☐ Dictionaries

☐ Functions

☐ if statements

☐ Loops

---

# Further Challenge

Research the Python library:

```
socket
```

Find out how Python can discover the real IP address of a website.

**Do not write code yet.**

Instead, answer:

- What does the `socket` library do?
- Why might programmers use it?
- How is it different from our simulated DNS dictionary?

---

# Success Criteria

I can...

☐ explain how DNS works.

☐ use a dictionary to store website information.

☐ retrieve values using keys.

☐ write a function.

☐ explain how this program models the Internet.

---

# Going Further

In Lesson 3, you will learn how computers follow communication rules called **network protocols**.

You will use Python again to simulate how devices exchange messages using these protocols.
