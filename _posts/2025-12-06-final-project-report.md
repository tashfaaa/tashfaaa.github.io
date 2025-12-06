---
layout: post
title: Final Project Report
tags: [programming]
comments: true
author: Tashfa Zafar
---

# Tashfa's Reading Buddy Tote!

As an avid reader who doesn't get a lot of time to read for myself at Williams, I wanted to create something that made reading feel a little more fun, cozy, and trackable—especially for moments on the go. The idea was to turn one of my many tote bags into a playful, interactive reading companion that gently encourages consistent reading. By giving visual feedback on reading progress and ambient lighting, the tote becomes both a practical tool and a personalized creative item. 

![tote](https://tashfaaa.github.io/floor.jpg)

Here's a comprehensive technical explanation of the project:

### Inputs:
Light Sensor (analog) - measures ambient light in the tote’s environment.
Switch (digital) - starts/stops official reading session.

### Outputs:

**RGB LED** - displays environment comfort:
1) ORANGE - optimal reading conditions (sufficient light)
2) PURPLE - dim light

**OTHER LEDs** - milestone indicators for a reading session:
- 1st LED - turns on 1s into reading, stays on
- 2nd LED - turns on 5s into reading, stays on
- 3rd LED - turns on 10s into reading, all three milestone LEDs blink briefly (for 2s thrice to celebrate milestone completion, then timer resets, starting the cycle again

## Comprehensive materials list
- 1 LilyPad Arduino, including on-board RGB LED
- 1 LilyPad Light Sensor
- 3 Pink LEDs
- A totebag
- Needle
- Sewing thread
- Conductive thread
- Scissors
- Emboridery floss (multiple random colors used)
- Small pieces of felt (left over from plushy project)

## Revised Paper Prototype
Screenshot of your revised paper prototype of your project
![updated paper prototype](https://tashfaaa.github.io/assets/img/finalestpaperprototype.png)

## Alligator Prototype
1 Photo of your alligator prototype working
![alligator prototype photo](https://tashfaaa.github.io/assets/img/circuit.png)

## It works!
Photo of at least 3 states of your working project (or video or gif) --> show what it looks like when it works
![maybe a gif of the working project](https://tashfaaa.github.io/assets/img/circuit.png)

## 3 tips for my past self:
Tip 1: Plan the circuit and the embellishments in conjunction! I sewed all my componenets and then came up with the decorative emboridery later which makes the two seem a bit disconnected. I think it would have been fun to experiment with incorporating the LEDs into my embroidered text directly for example.
Tip 2: Use shorter pieces of conductive thread!! It's truly so frustrating otherwise, with the thread frequently getting irreversibly tangled up or even breaking at the most inconvenient moments.
Tip 3: Do not neglect insulation! Initially I thought I could get away with minimum insulation, but at one point, two of my LEDs turned on simultaneously because their traces were accidently coming into contact with each other which was not supposed to happen at all at any point. Testing my project repeatedly and identifying such issues prompted me to insulate more of my traces and make the tote more functional.
