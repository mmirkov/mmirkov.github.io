---
id: 33
title: 'Биос &#8220;beep&#8221; кодове'
date: 2008-02-07T15:18:58+00:00
author: Мирков
layout: post
guid: https://mirkov.info/?p=33
permalink: /bios-beep-codes/
categories:
  - HowTo
  - Tech
---
AMI (American Megatrends International) BIOS Beep Codes.  
AMI BIOS uses beeps of the same length and pitch. The error is displayed as a number of beeps. For example, 4 beeps indicated a timer failure.  
BEEP CODE MEANING POSSIBLE CAUSE  
1 Beep (No video) Memory refresh failure Bad memory  
2 Beeps Memory parity error Bad memory  
3 Beeps Base 64K mem failure Bad memory  
4 Beeps Timer not operational Bad motherboard  
5 Beeps Processor error Bad processor  
6 Beeps 8042 Gate A20 failure Bad CPU or Motherboard  
7 Beeps Processor exception Bad processor  
8 Beeps Video memory error Bad video card or memory  
9 Beeps ROM checksum error Bad BIOS  
10 Beeps CMOS checksum error Bad motherboard  
11 Beeps Cache memory bad Bad CPU or motherboard

Award BIOS Beep Codes  
Award BIOS uses beeps of varying duration. A long beep will typically last for 2 seconds while a short beep will last only 1 second. Award BIOS also uses beeps of different frequency to indicate critical errors. If an Award BIOS detects that the CPU is overheating it may play a high pitched repeating beep while the computer is running.  
BEEP CODE MEANING POSSIBLE CAUSE  
1 Long, 2 Short Video adapter failure Bad video adapter  
Repeating (Endless loop) Memory error Bad memory or bad connection  
1 Long, 3 Short Video adapter failure Bad video adapter or memory  
High freq. beeps (while running) CPU is overheating CPU fan failure  
Repeating High, Low beeps CPU failure Bad processor

Phoenix BIOS Beep Codes  
Phoenix BIOS uses beep code patterns to indicate problems. In the table below the &#8216;-&#8216; indicates a brief pause between beeps.

Example: 1 &#8211; 1 &#8211; 2 would sound like BEEP BEEP BEEP BEEP  
BEEP CODE MEANING POSSIBLE CAUSE  
1 &#8211; 1 &#8211; 2 CPU / motherboard failure Bad CPU / motherboard  
1 &#8211; 1 &#8211; 3 CMOS read/write failure Bad motherboard  
1 &#8211; 1 &#8211; 4 BIOS ROM failure Bad BIOS chip  
1 &#8211; 2 &#8211; 1 Timer failure Bad motherboard  
1 &#8211; 2 &#8211; 2 DMA failure Bad motherboard  
1 &#8211; 2 &#8211; 3 DMA failure Bad motherboard  
1 &#8211; 3 &#8211; 1 Memory refresh failure Bad memory  
1 &#8211; 3 &#8211; 2 64K memory failure Bad memory  
1 &#8211; 3 &#8211; 3 64K memory failure Bad memory  
1 &#8211; 3 &#8211; 4 64K memory failure Bad memory  
1 &#8211; 4 &#8211; 1 Address line failure Bad memory  
1 &#8211; 4 &#8211; 2 Parity error Bad memory  
1 &#8211; 4 &#8211; 3 Timer failure Bad motherboard  
1 &#8211; 4 &#8211; 4 NMI port failure Bad motherboard  
2 &#8211; 1 &#8211; 1 64K memory failure Bad memory  
2 &#8211; 1 &#8211; 2 64K memory failure Bad memory  
2 &#8211; 1 &#8211; 3 64K memory failure Bad memory  
2 &#8211; 1 &#8211; 4 64K memory failure Bad memory  
2 &#8211; 2 &#8211; 1 64K memory failure Bad memory  
2 &#8211; 2 &#8211; 2 64K memory failure Bad memory  
2 &#8211; 2 &#8211; 3 64K memory failure Bad memory  
2 &#8211; 2 &#8211; 4 64K memory failure Bad memory  
2 &#8211; 3 &#8211; 1 64K memory failure Bad memory  
2 &#8211; 3 &#8211; 2 64K memory failure Bad memory  
2 &#8211; 3 &#8211; 3 64K memory failure Bad memory  
2 &#8211; 3 &#8211; 4 64K memory failure Bad memory  
2 &#8211; 4 &#8211; 1 64K memory failure Bad memory  
2 &#8211; 4 &#8211; 2 64K memory failure Bad memory  
2 &#8211; 4 &#8211; 4 64K memory failure Bad memory  
2 &#8211; 4 &#8211; 4 64K memory failure Bad memory  
3 &#8211; 1 &#8211; 1 Slave DMA failure Bad motherboard  
3 &#8211; 1 &#8211; 2 Master DMA failure Bad motherboard  
3 &#8211; 1 &#8211; 3 Interrupt controller failure Bad motherboard  
3 &#8211; 1 -4 Slave IC failure Bad motherboard  
3 &#8211; 2 -2 Interrupt Controller failure Bad motherboard  
3 &#8211; 2 &#8211; 3   
3 &#8211; 2 &#8211; 4 Keyboard control failure Bad motherboard  
3 &#8211; 3 &#8211; 1 CMOS batter failure Bad CMOS battery  
3 &#8211; 3 &#8211; 2 CMOS configuration error Incorrect setting  
3 &#8211; 3 &#8211; 3   
3 &#8211; 3 &#8211; 4 Video memory failure Bad video card or memory  
3 &#8211; 4 &#8211; 1 Video init failure Bad video card or memory  
4 &#8211; 2 &#8211; 1 Timer failure Bad motherboard  
4 &#8211; 2 &#8211; 2 CMOS shutdown failure Bad motherboard  
4 &#8211; 2 &#8211; 3 Gate A20 failure Bad motherboard  
4 &#8211; 2 &#8211; 4 Unexpected interrupt Bad processor  
4 &#8211; 3 &#8211; 1 RAM test failure Bad memory  
4 &#8211; 3 &#8211; 3 Timer failure Bad motherboard  
4 &#8211; 3 &#8211; 4 RTC failure Bad motherboard  
4 &#8211; 4 &#8211; 1 Serial port failure Bad motherboard  
4 &#8211; 4 &#8211; 2 Parallel port failure Bad motherboard  
4 &#8211; 4 &#8211; 3 Coprocessor failure Bad motherboard or CPU.  
9 &#8211; 2 &#8211; 1 Video adapter incompatibility Use a different brand of video card