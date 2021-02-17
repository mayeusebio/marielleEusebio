---
layout: post
title:  "A Hydroponic Herb Garden (Pt 1)"
date:   2021-02-16 16:29:00 -0700
categories: personal
---

I love cilantro. I also recently learned about the communication protocols I2C and SPI and how to interface with modules using it. The two don't seem connected but when I had to come up with a end of the quarter project for my Embedded Systems class, I thought about growing cilantro. Though I haven't had any experience hydroponically growing anything before this project, I thought my love for cilantro could motivate me to finish anything.

My project could be compared to a bare bones version of an AeroGarden, except much less sleek looking and a much lower price tag. 

This will be a series documenting this project. 
The idea is simple. The conditions for growing cilantro must be met. To monitor it's environment I would employ the use of two sensors: a soil temperature and moisture sensor, and a light sensor. The pH level sensor was a bit too much of an expense and I decided for simplicities sake to leave it out. Our project required a few things from us to include:
- It had to include two-way communication using AWS
- Had to use the TI CC3200 Launchpad
- We had to integrate I2C and SPI communication somehow

The project is very open ended.