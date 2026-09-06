# TryHackMe — Offensive Security Intro

## Overview

Completed the TryHackMe "Offensive Security Intro" room as part of my hands-on cybersecurity training.

This room introduced the fundamentals of offensive security and provided hands-on experience identifying weaknesses in a simulated web application.

## Objectives

- Understand the purpose of offensive security
- Learn how attackers identify exposed functionality
- Practice using the command line
- Use `dirb` to discover hidden web directories
- Identify a security weakness in a simulated web application
- Understand how attackers can take advantage of improperly protected functionality

## Tools Used

- Linux Terminal
- DIRB
- Web Browser
- TryHackMe Lab Environment

## What I Did

### 1. Learned About Offensive Security

I learned that offensive security involves thinking from an attacker's perspective to identify weaknesses before real attackers can exploit them.

The goal is to find vulnerabilities in a controlled and authorized environment so they can be fixed.

### 2. Worked With a Simulated Web Application

I used the TryHackMe virtual lab environment to interact with a simulated banking application called FakeBank.

This provided a safe environment to practice security testing without targeting a real system.

### 3. Used DIRB to Discover Hidden Pages

I used the Linux terminal and the `dirb` tool to scan the simulated website for hidden directories and pages.

Command used:

```bash
dirb http://fakebank.thm
