---
id: 273
title: Използване на SCP пример
date: 2008-10-22T16:34:27+00:00
author: Мирков
layout: post
guid: http://mirkov.info/?p=273
permalink: /scp-primer/
categories:
  - Uncategorized
---
<p class="content">
  За да изпратите файл:<br /> $ scp ./file username@domain.com:
</p>

За да изпратите директория:  
$ scp -r ./dir username@domain.com:

За да копирате файл:  
$ scp username@domain.com:~/dir/file .

За да копирате директория:  
$ scp -r username@domain.com:~/dir .

За повече информация може да прочетете man(1) scp.