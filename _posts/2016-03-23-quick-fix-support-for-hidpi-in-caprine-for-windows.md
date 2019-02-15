---
id: 783
title: 'Quick Fix: Support for HiDPI  in Caprine  for Windows'
date: 2016-03-23T23:45:02+00:00
author: Miroslav Mirkov
layout: post
guid: http://mirkov.info/?p=783
permalink: /quick-fix-support-for-hidpi-in-caprine-for-windows/
categories:
  - HowTo
tags:
  - caprine
  - facebook messenger
  - messenger
---
In order to fix the wired looking (small) font of Caprine for Windows you just have to change (add) the &#8220;zoomFactor&#8221; parameter in ressources\app\index.js right after webPreferences:  
zoomFactor: 1.2,

<a href="http://mirkov.info/wp-content/uploads/2016/03/Screenshot_1.png" rel="attachment wp-att-784"><img class="aligncenter size-full wp-image-784" src="http://mirkov.info/wp-content/uploads/2016/03/Screenshot_1.png" alt="Screenshot_1" width="992" height="251" srcset="http://mirkov.info/wp-content/uploads/2016/03/Screenshot_1.png 992w, http://mirkov.info/wp-content/uploads/2016/03/Screenshot_1-300x76.png 300w, http://mirkov.info/wp-content/uploads/2016/03/Screenshot_1-768x194.png 768w" sizes="(max-width: 992px) 100vw, 992px" /></a>

Save the file and re-run the app. The font should be readable now.

More about Caprine &#8211; <a href="https://github.com/sindresorhus/caprine" target="_blank">https://github.com/sindresorhus/caprine</a>