---
layout: post
title: Android APK Instrumentation
---

In my current project, I have to decompile the popular apks from Google Play, modify them and repack them automatically.

We will use ASM for this project. We select 20 applications from Google Play store and apply delta-debugging so that we make sure each modification we did to the application will not result in error or crash.


