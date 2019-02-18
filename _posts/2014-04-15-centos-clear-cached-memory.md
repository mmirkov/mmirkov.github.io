---
id: 687
title: 'CentOS: Clear cached memory'
date: 2014-04-15T22:16:10+00:00
author: Miroslav Mirkov
layout: post
guid: https://mirkov.info/?p=687
permalink: /centos-clear-cached-memory/
categories:
  - HowTo
---
Use the following command to clear you cached memory:

<pre>root@linux [~]# echo 1 &gt; /proc/sys/vm/drop_caches</pre>

[<img class="aligncenter wp-image-688 size-full" src="https://mirkov.info/wp-content/uploads/2014/04/cache.png" alt="clear cached memory" width="750" height="277" srcset="https://mirkov.info/wp-content/uploads/2014/04/cache.png 750w, https://mirkov.info/wp-content/uploads/2014/04/cache-300x110.png 300w" sizes="(max-width: 750px) 100vw, 750px" />](https://mirkov.info/wp-content/uploads/2014/04/cache.png)