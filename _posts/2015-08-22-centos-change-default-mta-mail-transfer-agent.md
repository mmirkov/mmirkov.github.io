---
id: 752
title: 'CentOS: Change default MTA (Mail Transfer Agent)'
date: 2015-08-22T17:19:34+00:00
author: Miroslav Mirkov
layout: post
guid: http://mirkov.info/?p=752
permalink: /centos-change-default-mta-mail-transfer-agent/
categories:
  - HowTo
---
Here&#8217;s a simple way to change your default MTA on CentOS: 

<pre># alternatives --config mta

There are 2 programs which provide 'mta'.

  Selection    Command
-----------------------------------------------
*+ 1           /usr/sbin/sendmail.sendmail
   2           /usr/sbin/sendmail.ssmtp

Enter to keep the current selection[+], or type selection number: 2

# sendmail -V
sSMTP 2.61 (Not sendmail at all)</pre>