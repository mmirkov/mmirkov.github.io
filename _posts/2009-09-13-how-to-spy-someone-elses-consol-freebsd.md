---
id: 478
title: 'Kак да шпионираме чужда конзола &#8211; FreeBSD'
date: 2009-09-13T08:54:11+00:00
author: Мирков
layout: post
guid: http://mirkov.info/?p=478
permalink: /how-to-spy-someone-elses-consol-freebsd/
categories:
  - Uncategorized
---
Много просто<img src='http://mirkov.info/wp-includes/images/blank.gif' alt=':)' class='wp-smiley smiley-2' /> 

Първо трябва да компилираме &#8220;snp&#8221; модула, който се намира в &#8220;/usr/src/sys/modules/snp&#8221;

\# cd /usr/src/sys/modules/snp/  
\# make && make install

След като го компилираме си избираме цел за шпиониране<img src='http://mirkov.info/wp-includes/images/blank.gif' alt=':)' class='wp-smiley smiley-2' />  
\# w  
9:16PM up 98 days, 52 mins, 2 users, load averages: 0.08, 0.06, 0.00  
USER TTY FROM LOGIN@ IDLE WHAT  
eraser p0 old.smrad.net 9:06PM &#8211; w  
eraser p1 old.smrad.net 9:16PM &#8211; -bash (bash)

Като изберем цел, просто правим:

\# watch p1