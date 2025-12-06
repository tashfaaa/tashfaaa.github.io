---
layout: post
title: Final Project Report
tags: [programming]
comments: true
author: Tashfa Zafar
---

# Tashfa's Reading Buddy Tote!

As an avid reader who doesn't get a lot of time to read for myself at Williams, I wanted to create something that made reading feel a little more fun, cozy, and trackable—especially for moments on the go. The idea was to turn one of my many tote bags into a playful, interactive reading companion that gently encourages consistent reading. By giving visual feedback on reading progress and ambient lighting, the tote becomes both a practical tool and a personalized creative item, with decorative embroidered books that double as insulation for some of my traces, and also some embroidered text:

![tote](https://tashfaaa.github.io/assets/img/floor.jpg)

![embroidery](https://tashfaaa.github.io/assets/img/read.jpg)

Here's a comprehensive technical explanation of the project:

### Inputs:

- Light Sensor (analog) - measures ambient light in the tote’s environment.
- Switch (digital) - starts official reading session.

### Outputs:

**RGB LED** - displays environment comfort:
- ORANGE - optimal reading conditions (sufficient light)
- PURPLE - dim light

**OTHER LEDs** - milestone indicators for a reading session (time can be changed according to one's reading goals):
- 1st LED - turns on 1s into reading, stays on
- 2nd LED - turns on 5s into reading, stays on
- 3rd LED - turns on 10s into reading, all three milestone LEDs blink briefly (for 2s thrice to celebrate milestone completion, then timer resets, starting the cycle again

## Comprehensive list of materials I used:
- 1 LilyPad Arduino, including on-board RGB LED
- 1 LilyPad Light Sensor
- 3 Pink LEDs
- A totebag
- Needle
- Sewing thread
- Conductive thread
- Scissors
- Embroidery floss (multiple random colors used)
- Small pieces of felt for insulation (left over from plushy project)

## Revised Paper Prototype
After getting feedback on my original circuit, I made some edits, e.g. giving the switch it's own pin to make it possible to read whether it's on or off and shape LED behaviors accordingly.

![updated paper prototype](https://tashfaaa.github.io/assets/img/finalestpaperprototype.png)

## Alligator Prototypes
Here's my working alligator prototypes depicting different stages of the program.

With the first LED in the series turned on:
![alligator prototype photo](https://tashfaaa.github.io/assets/img/FinAlProto.jpg)


With the first two sets of LEDs in the series turned on:
![board prototype](https://tashfaaa.github.io/assets/img/FinBoard.jpg)

## It works!

Purple light when there isn't sufficient light/with the light sensor covered by a book:

![purple](https://tashfaaa.github.io/assets/img/purp.jpg)

Orange light on (optimal light!) alongside the three pink LEDs turning on in succession before blinking together at the 10 second mark and restarting the cycle:

![1 pink on](https://tashfaaa.github.io/assets/img/fin1.jpg)

![2 pink on](https://tashfaaa.github.io/assets/img/fin2.jpg)

![3 pink on](https://tashfaaa.github.io/assets/img/fin3.jpg)

Tada :D
![gif of the working project](https://tashfaaa.github.io/assets/img/finalest.gif)

## 3 tips for my past self:
Tip 1: Plan the circuit and the embellishments in conjunction! I sewed all my componenets and then came up with the decorative emboridery later which makes the two seem a bit disconnected. I think it would have been fun to experiment with incorporating the LEDs into my embroidered text directly for example.
Tip 2: Use shorter pieces of conductive thread!! It's truly so frustrating otherwise, with the thread frequently getting irreversibly tangled up or even breaking at the most inconvenient moments.
Tip 3: Do not neglect insulation! Initially I thought I could get away with minimum insulation, but at one point, two of my LEDs turned on simultaneously because their traces were accidently coming into contact with each other which was not supposed to happen at all at any point. Testing my project repeatedly and identifying such issues prompted me to insulate more of my traces and make the tote more functional.
