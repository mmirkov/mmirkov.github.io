---
id: 647
title: 'gem install rmagick &#8211; Can’t find Magick-config (CentOS 6)'
date: 2014-02-01T19:51:08+00:00
author: Miroslav Mirkov
layout: post
guid: https://mirkov.info/?p=647
permalink: /gem-install-rmagick-cant-find-magick-config-centos-6/
categories:
  - Uncategorized
---
In case you receive the mentioned error while trying to install rmagick then simply issue the following: 

<pre># yum install ImageMagick-devel</pre>

Once ImageMagick-devel is installed then you can retry installing rmagick using: 

<pre># gem install rmagick</pre>