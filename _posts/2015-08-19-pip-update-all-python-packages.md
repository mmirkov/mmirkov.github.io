---
id: 751
title: 'PIP &#8211; update all Python packages'
date: 2015-08-19T20:01:04+00:00
author: Miroslav Mirkov
layout: post
guid: http://mirkov.info/?p=751
permalink: /pip-update-all-python-packages/
categories:
  - HowTo
---
<pre>pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs pip install -U</pre>