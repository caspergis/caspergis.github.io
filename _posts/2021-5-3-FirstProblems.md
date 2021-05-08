---
title: First problems
layout: post
---

## 1. Maven build system and NetBeans platform.  
Having had some problems with Ant when developing other programs on NetBeans Platform, and having had a positive experience with the maven Geotools tutorial, I wanted to use maven for CasperGis. 
 Unfortunately it was not possible :( - I choose Ant :)
## 2. Toolbox or toolbox window.  
I have a problem with choosing the method of presenting the tool buttons.
 I can choose from:
 1. Classic toolbar - as in many Windows programs.
 2. Minimal toolbar with a floating window - like in OpenJump.
 3. Toolbox window - as in uDig.  
 The option I like the most is 2. NetBeans platform does not allow you to create a JDialog without a title bar,
 which as a result does not look good.  Option 3 seems to be the easiest to implement.
  I will deploy option 1 but I will experiment with the use of JPanel to her floating tool window.  
