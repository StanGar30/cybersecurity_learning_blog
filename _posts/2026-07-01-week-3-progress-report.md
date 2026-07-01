---
title: Week 3 Progress Report
date: 2026-07-01 10:00:00 +0200
categories: [Progress]
tags: [thm, htb, linux, beginner, web-security]
---

# Week 3 Progress Report

This week I continued studying on TryHackMe and Hack The Box, while also practicing in my own local lab environment.

## What I Studied

### TryHackMe

This week I worked through several beginner-friendly rooms and modules:

* Become a Defender
* Linux Fundamentals Part 1
* Linux Fundamentals Part 2
* Linux Fundamentals Part 3
* Guided Pentest: Infrastructure
* Dive Into Pentesting
* Cyber Kill Chain
* Penetration Testing Frameworks

### Hack The Box

I finally finished **Linux Fundamentals** and started the **Web Penetration Tester** path. So far, it feels very useful, practical, and straight to the point.

Completed modules:

* Web Requests
* Introduction to Web Applications

## What I Learned

This week helped me connect basic Linux knowledge with real security testing concepts.

I practiced and studied:

* Hydra
* SearchSploit
* Metasploit basics
* URL encoding
* Sensitive data exposure
* HTML injection
* Cross-Site Scripting, also known as XSS
* Cross-Site Request Forgery, also known as CSRF

I also learned more about different penetration testing methodologies and standards:

* ISSAF
* OSSTMM
* OWASP WSTG
* NIST SP 800-115
* PTES

The main takeaway for me is that penetration testing is not just about running tools. A good test needs structure: reconnaissance, enumeration, exploitation, documentation, and reporting.

## Challenges and Practice

I started practicing on my own website/platform in a controlled lab environment. Surprisingly, the first simple `curl` request already revealed several security issues and misconfigurations that I need to investigate and fix.

I also wrote two small scripts connected to a local LLM:

1. **Librarian** — searches through my local cheat sheets and notes based on a description.
2. **Googler** — searches the internet based on a description and returns a short summary.

This was useful because I started building my own small workflow for learning, searching, and organizing information faster.

I also spent some time practicing:

* HTML injection
* XSS
* CSRF

These topics are especially interesting because they show how small mistakes in input handling, output encoding, and request validation can lead to real security problems.

## Interesting Findings

One of the most interesting things this week was seeing how powerful basic tools can be. Even simple commands like `curl` can reveal a lot about how an application behaves.

I also found SearchSploit and Metasploit very useful for understanding how known vulnerabilities are researched and tested in lab environments.

Another important point was learning that frameworks like OWASP WSTG, PTES, and NIST SP 800-115 help keep testing organized instead of random.

## Goals for Next Week

### TryHackMe

Continue going through the modules in order and complete a few more rooms.

### Hack The Box

Continue the Web Penetration Tester path and complete more modules step by step.

### Personal Lab

Keep testing my own platform and start fixing the issues I already found. I also want to improve my notes and write short reports for each topic I practice.
