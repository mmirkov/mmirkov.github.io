---
id: 587
title: Optimize MySQL tables
date: 2013-04-30T11:07:01+00:00
author: Мирков
layout: post
guid: https://mirkov.info/?p=587
permalink: /optimize-mysql-tables/
categories:
  - Tech
---
Optimize single database table:

<pre>mysql&gt; OPTIMIZE TABLE my_table</pre>

&nbsp;

Optimize entire database:

<pre>shell# mysqlcheck -op -u root your_database_name</pre>

&nbsp;

Optimize ALL databases:

<pre>shell# mysqlcheck -u root -p --auto-repair --check --optimize --all-databases</pre>