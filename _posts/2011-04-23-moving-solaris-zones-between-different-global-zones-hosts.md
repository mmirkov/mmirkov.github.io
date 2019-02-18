---
id: 555
title: Moving solaris zones between different global zones (hosts)
date: 2011-04-23T15:18:23+00:00
author: Мирков
layout: post
guid: https://mirkov.info/?p=555
permalink: /moving-solaris-zones-between-different-global-zones-hosts/
categories:
  - Tech
---
Suppose you have a Solaris zone (ZONENAME) on one host and want to move it on other global zone.  
  
On first server:  


<pre>1. zoneadm -z ZONENAME halt
2. zoneadm -z ZONENAME detach
3. cd $ZONEHOME
4. tar -cf ../zonename.tar .
5. scp ../zonename.tar user@server2:/$ZONEPATH</pre>

On the second server:  


<pre>1. mkdir $ZONEHOME
2. cd $ZONEHOME
3. tar -xf ../zonename.tar .
4. zonecfg -z ZONENAME
>create -a $ZONEHOME
>exit
5. zoneadm -z ZONENAME attach
6. zoneadm -z ZONENAME boot</pre>

You&#8217;re good to go<img src='https://mirkov.info/wp-includes/images/blank.gif' alt=':)' class='wp-smiley smiley-2' />