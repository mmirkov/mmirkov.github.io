---
id: 328
title: 'Google Chrome 0.4.154.29 &#8211; update'
date: 2008-12-04T14:22:49+00:00
author: Мирков
layout: post
guid: https://mirkov.info/?p=328
permalink: /google-chrome-041542-update/
categories:
  - Tech
---
Новите неща са:

Gears Cross-Origin Worker Vulnerability  
CVE: CVE-2008-5258  
A vulnerability in Gears could allow an attacker to run code in the context of a site that serves user-controlled files. To exploit this, an attacker needs to upload a malicious file to the victim&#8217;s site and convince the user to allow the attacker&#8217;s site to use Gears.

Severity: High. Even though this requires convincing users to allow a third-party site to use Gears, it could allow data theft and cross-site scripting on sites hosting user-created content, even those that do not use Gears.  
Credit: Thanks to Yair Amit, Senior Security Researcher, IBM Rational Application Security Research Team for responsibly reporting the issue to Google.

This release also contains a fix to stop crashes while dragging tabs on computers running Windows Vista.