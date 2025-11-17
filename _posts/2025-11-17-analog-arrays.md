---
layout: post
title: Analog Arrays
tags: [programming]
comments: true
author: Tashfa Zafar
---

This assignment involved creating a program that randomly controls LEDs connected to PWM pins on our arduino. Every second, the program picks one PWM pin from a list stored in an array. If the selected pin is currently on, the program turns it off; if it’s off, it turns on with a random brightness. A second array keeps track of each pin’s on/off state so the program knows whether to turn a pin on or off when it’s chosen. 

Here's photo of my program in action:

![three sets of leds on](https://tashfaaa.github.io/assets/img/arrays.jpg)

{: .box-note}
**Tip:** Always use the Serial Monitor to track what the code is doing even if might not seem particularly relevant for a particular task!!!! It helped me catch that my pink LED was faulty. The monitor showed it was supposed to turn on with a specific brightness, but the LED never lit, so I figured it wasn’t a code problem but a hardware issue that I was able to fix by replacing the LED with a different one. 

![serial monitor](https://tashfaaa.github.io/assets/img/arrayssm.png)
