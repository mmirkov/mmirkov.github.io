---
id: 791
title: 'Enable &#8220;Subject:&#8221; logging in Postfix'
date: 2016-04-21T22:06:27+00:00
author: Miroslav Mirkov
layout: post
guid: https://mirkov.info/?p=791
permalink: /enable-subject-logging-in-postfix/
categories:
  - HowTo
---
Edit the Postfix&#8217;s **main.cf** file and add the following line (or uncomment it):

<pre>header_checks = regexp:/etc/postfix/header_checks</pre>

Create **/etc/postfix/header_checks** file and add the following line:

<pre>/^subject:/ WARN</pre>

Finally, reload/restart Postfix. From now on there will be a **&#8220;warrning: header subject&#8221;** in your maillog.