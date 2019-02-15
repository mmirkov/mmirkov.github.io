---
id: 310
title: 'Полезни команди с NETSH &#8211; Network Services Shell'
date: 2008-11-26T17:16:25+00:00
author: Мирков
layout: post
guid: http://mirkov.info/?p=310
permalink: /network-services-shell/
categories:
  - Tech
---
Reset Internet Protocol (TCP/IP)

Ако поради някаква причина сте били заразени с някакви боклуци и tcp/ip прокола Ви се е прецакал, опитайте следната команда в command prompt (start->run->cmd->ok):

netsh int ip reset  
или  
netsh int ip reset C:\tcplog.txt &#8211; ако искате да логнете output-а и да видите с подробности какво се е случило. Ще бъде записан лог файл в C:\tcplog.txt

Аналогично ако Ви се е прецакал winsock-а:

netsh winsock reset catalog