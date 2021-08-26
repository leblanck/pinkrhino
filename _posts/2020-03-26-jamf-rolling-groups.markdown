---
layout: post
title: Jamf Rolling Update Groups
date: 2020-03-26 13:16:39 -0500
tags: [Jamf, Updates, Bash]
image: '/images/covers/cover29.jpg'
description: Creating a rolling (phased) update process similar to SCCM
---
**Coming Soon!**

**tl;dr** This process was created to replicate something *similar* to that of phased roll-outs in SCCM. Groups get increasingly larger as the roll out continues. This process is intended to be used with Jamf. It is available on my [github](https://github.com/leblanck/macOS-Scripts). If you'd like to learn more about this process please continue below!

**What, Why, & How?**

If there is one thing I wish that Jamf had built-in it would be a rolling update feature. Something where it will auto populate/scale based on total enrolled machines. 

![Script Notes](/images/screenshots/rolling-command.png)

I have little-to-no experience in SCCM but I do recall co-workers being able to slowly roll-out updates/softare using 'phased update groups'. Doing so would allow to start deploying to 10% of devices, then the following 15%, 25%, 50% each time. 

![Groups Seen in Jamf](/images/screenshots/rollingGroup-Jamf.png)

I am often asked by Product Owners/Scrum Masters if this is easily done and until now my answer was, unfortunatley, no (at least not in an automated, easy way :( ).

![Script Notes](/images/rollingNotes.jpeg)
