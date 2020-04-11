---
title: "Debugging for Yahoos"
date: 2020-04-11T10:46:54-06:00
draft: false
---

# Debugging for Yahoos

This week I got some work for a client who came back reporting some buggy behavior on some equipment my company had built for them. **I had delivered a couple of patches on the software already this year**. The equipment was custom built by us to be able to control the current on various channels coming out of a power supply box. 


# Hide and seek: day 1

The software we created to control the boxes was pretty small so I didn't imagine there would be too many places for a bug to hide.

The first bug they reported I was able to fix and patch in under a day, the second one took me about a week. This time, I requested three supply boxes back from the client so I could get straight to the point and reproduce the bug.

I set up a test bench with some loads hooked up to the output channels and before the end of the day I was able to reproduce the bug. But after several hours I was still clueless as to what was causing the malfunction.

![A typical debugging experience](finding-a-bug.jpg)

## Day 2

Starting the second day I resolved to be devout in my note taking. This turned out to be a game changer for the obvious reason that my memory array has a length of seven, but also because once I started writting down conditions for each successive test I realized just how many factors I was capable of varying.

## To be continued...

At the end of the second day I started to develop a theory that the bug was actually hardware related, even though we previously ruled that out. We haven't pinned down the cause yet, but I left the office feeling like I learned a lot from the experience. Take detailed notes, and always challenge your assumptions.
