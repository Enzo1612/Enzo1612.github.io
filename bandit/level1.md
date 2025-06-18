---
layout: post
title:  "OverTheWire Bandit Level0 Walkthrough"
date: 2025-06-25
categories: ctf walkthrough overthewire bandit
collection: bandit
permalink: /bandit/level0
---

## OverTheWire Bandit Level 0

### **Objective**


---

### **Approach**

**Initial Reconnaissance:**
* Log in to `bandit0` using:*
`ssh bandit0@bandit.labs.overthewire.org -p 2220`

**Problem Solving Steps:**
List the files/folders in the current directory.
```bash
ls
```
**Output:**
```bash
bandit0@bandit:~$ ls
readme
```
Print the readme file in the terminal.
```bash
cat readme
```
**Output:**
```bash
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```


---

### **Solution**

The password for `bandit1` is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If



---

### **Key Takeaways**
The first thing you should do when connecting to a new machine, is listing the files and directories.
To print the content of a file, you use the `cat` command.

---

### **Next Level**

* **[Bandit Level1](/bandit/level1)**
