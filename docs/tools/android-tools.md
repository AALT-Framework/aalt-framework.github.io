---
layout: default
title: Android available tools
nav_order: 2
has_children: false
permalink: /tools/android-tools
parent: Tools
---

# Android available tools 

These are the tools available on Android that can be used to check the accessibility of apps.

Check which one is most appropriate for your context. Ideally, use all of them!

| Tool | Test level | Running environment | What you need to do |
| ------------- | ------------- | ------------- | ------------- |
| **Accessibility Scanner** | Bit tests | Instrumented | Run and verify the app screen by screen |
| **UI Automator** | Big tests | Instrumented | Write automated UI tests that check accessibility |
| **Espresso** | Medium and big tests | Instrumented | Call API AccessibilityChecks from the root view of each screen |
| **Roboletric** | Small tests | Local | **Use the AATK** | 
| **Lint** | Static checks | Local | Check the warnings | 