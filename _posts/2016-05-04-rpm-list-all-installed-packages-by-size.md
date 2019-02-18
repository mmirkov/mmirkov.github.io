---
id: 795
title: 'RPM: List all installed packages by size'
date: 2016-05-04T20:19:23+00:00
author: Miroslav Mirkov
layout: post
guid: https://mirkov.info/?p=795
permalink: /rpm-list-all-installed-packages-by-size/
categories:
  - HowTo
tags:
  - CentOS
  - linux
  - packages
  - rpm
  - shell
---
<pre>shell$ rpm -qa --queryformat '%10{SIZE}\t%{NAME}\n' | sort -k1,1n </pre>