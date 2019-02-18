---
id: 575
title: 'Fix: send-mail: warning: inet_protocols: IPv6 support is disabled: Address family not supported by protocol'
date: 2013-01-23T16:13:46+00:00
author: Мирков
layout: post
guid: https://mirkov.info/?p=575
permalink: /fix-send-mail-warning-inet_protocols-ipv6-support-is-disabled-address-family-not-supported-by-protocol/
categories:
  - Tech
---
Here&#8217;s how to fix the following Postfix issue:

send-mail: warning: inet_protocols: IPv6 support is disabled: Address family not supported by protocol  
send-mail: warning: inet_protocols: configuring for IPv4 support only  
postdrop: warning: inet_protocols: IPv6 support is disabled: Address family not supported by protocol  
postdrop: warning: inet_protocols: configuring for IPv4 support only

\# /usr/sbin/postconf | grep inet_protocols  
inet_protocols = all

\# vi /etc/postfix/main.cf

Search for: inet\_protocols and change it from &#8220;inet\_protocols = all&#8221; to &#8220;inet_protocols = ipv4&#8221;  
Save /etc/postfix/main.cf and and restart Postfix service:

\# /etc/init.d/postfix restart