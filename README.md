# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQLi

![](https://github.com/acary/fb-cp-wk8/blob/master/sqli.gif)

Vulnerability #2: Session Hijacking

![](https://github.com/acary/fb-cp-wk8/blob/master/session-hijack.gif)


## Green

Vulnerability #1: User Enumeration

Message to valid user has bold text; no bold text if attempted user is not valid

![](https://github.com/acary/fb-cp-wk8/blob/master/user-enum1.gif)

Vulnerability #2: Cross-Site Scripting (CSS) via Contact Form

![](https://github.com/acary/fb-cp-wk8/blob/master/xss-contact.gif)

## Red

Vulnerability #1: IDOR

![](https://github.com/acary/fb-cp-wk8/blob/master/idor.gif)

Vulnerability #2: CSRF

![](https://github.com/acary/fb-cp-wk8/blob/master/csrf.gif)
