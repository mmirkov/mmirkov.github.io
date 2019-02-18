---
id: 566
title: HOWTO INSTALL RKHUNTER (QUICK GUIDE)
date: 2012-10-22T19:06:48+00:00
author: Мирков
layout: post
guid: https://mirkov.info/?p=566
permalink: /howto-install-rkhunter-quick-guide/
categories:
  - HowTo
  - Tech
---
HOWTO INSTALL RKHUNTER (QUICK GUIDE)  
1. Download the later rkhunger version from sf.net: http://sourceforge.net/projects/rkhunter/  
2. shell# tar -zxvf tar -zxvf rkhunter-1.4.0.tar.gz  
3. shell# cd rkhunter-1.4.0  
4. shell# ./installer.sh &#8211;layout default &#8211;install  
5. shell# /usr/local/bin/rkhunter &#8211;update  
6. shell# /usr/local/bin/rkhunter &#8211;propupd  
7. shell# vi /etc/cron.daily/rkhunter.sh  
8: Add the following configuration to rkhunter.sh cron script:

-=-=- cut -=-=-  
#!/bin/sh  
(  
/usr/local/bin/rkhunter &#8211;versioncheck  
/usr/local/bin/rkhunter &#8211;update  
/usr/local/bin/rkhunter &#8211;cronjob &#8211;report-warnings-only  
<img src='https://mirkov.info/wp-includes/images/blank.gif' alt=')' class='wp-smiley smiley-2' /> | /bin/mail -s &#8216;rkhunter Daily Run (PutYourServerNameHere)&#8217; your@email.here  
-=-=- end -=-=-

9. chmod 700 /etc/cron.daily/rkhunter.sh  
10. You&#8217;re good to go<img src='https://mirkov.info/wp-includes/images/blank.gif' alt=':)' class='wp-smiley smiley-2' />