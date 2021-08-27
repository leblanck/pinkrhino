---
layout: post
title: SDK .NET Error when creating new UE4 C++ Project
date: 2021-08-26 10:37:16 -0500
tags: [Troubleshooting, UE4, SDK, .NET, Engine]
image:  '/images/SDKInstall.PNG'
description: SDK, SMH 
featured: true
---

 <div class="gallery-box">
    <div class="gallery">
      <img src="/images/UE4_LaunchNewProj_NETError.PNG">
    </div>
  </div> 

### Problem

This may be a simple problem, but it stumped me for quite a while when creating my first C++ based prject in Unreal Engine 4. I continued to receive the above error regardless of how I thought I had installed VS, updated UE4, re-installed both, etc.  Turns out all I needed was a fresh install of the .NET SDK. (duh)

### Solution

![SDK Install](/images/SDKInstall.PNG)

The solution to this issue happens to be an outdated (or missing) version of .NET & the .NET SDK Framework. To update this you can follow the below instructions:

* Launch Microsoft Visual Studio Installer
* Next to your installed version of VS select Modify
* Select the 'Individual Components' Tab and mark the checkbox next to the latest version of the .NET SDK


