---
layout: post
title: Spice Rack
subtitle: Kitchen Tyranny
image: /img/projects/spicerack/thumbnail.jpg
tags: [project, electrical, software, long term]
---
Our dorm's kitchen is nominally disgusting. This is to be expected when 30 students are forced to use the same kitchen. 

George Bush once encouraged us all to be vigilant. I don't think he was asking me to set up a system of cameras in our kitchen to find dirty-dish perpetrators, but I did it anyways. We must, of course, be vigilant. 

![](/img/projects/spicerack/1.jpg)

Spice-rack is a Flask application that's designed to keep watch over our sinks. It lives on a small server balanced on top of a fridge. Noodly camera appendages branch out from it.

![](/img/projects/spicerack/2.jpg)

Every ten seconds, a background thread takes a series of snapshots. Motion is tracked from snapshot to snapshot using OpenCV.

Dirty dishes appear when people appear, and people tend to move around. A C3.js graph that shows kitchen movement over time lets our hall's residents sweep through the kitchen's history and track down perpetrators.

![](/img/projects/spicerack/3.jpg)

Evidence can then be collected and spammed at the perpetrators.

![](/img/projects/spicerack/4.jpg)

There is, of course, a leaderboard.

![](/img/projects/spicerack/5.jpg)

I don't think anyone needs to point out the ethical dilemmas associated with wiring a public space with cameras. Hence, the OpenID authorization system and various other protection mechanisms.

![](/img/projects/spicerack/6.jpg)

![](/img/projects/spicerack/7.jpg)

Our kitchen now looks more presentable than ever. Thank you, NSA. I'm sure you're watching anyways.