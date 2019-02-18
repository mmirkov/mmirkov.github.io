---
id: 495
title: 'from imagecreatefrom png:      gd-png:  fatal libpng error: [00][00][00][00]: unknown critical chunk'
date: 2009-10-19T18:39:53+00:00
author: Мирков
layout: post
guid: https://mirkov.info/2009/10/from-imagecreatefrom-png-gd-png-fatal-libpng-error-00000000-unknown-critical-chunk/
permalink: /from-imagecreatefrom-png-gd-png-fatal-libpng-error-00000000-unknown-critical-chunk/
categories:
  - HowTo
  - Tech
---
Ако някой се е сблъсквал със следния проблем (php5-gd / FreeBSD 7.2) описан в заглавието на поста, то решението е следното:

portupgrade -f png  
portupgrade -fr png

Това се отнася за FreeBSD.