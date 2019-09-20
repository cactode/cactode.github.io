---
layout: post
title: ML Cat Delivery System
subtitle: AKA Laser Guided Cats
image: /img/projects/catdelivery/thumbnail.png
tags: [project, mechanical, software, short term]
---
Cats follow lasers. Lasers can be aimed by computers. Computers can run YOLO. YOLO can detect cats. We now have a beautiful hackathon project.

<iframe width="560" height="315" src="https://www.youtube.com/embed/4MIq9EfABlo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

I worked on this with [Shreyas Kapur](http://www.shreyaskapur.com) at HackMIT over the course of 24 hours. A small custom pan-tilt system guides cats around with a Microcenter $4 laser pointer. A webcam running a YOLO-based model customized with IBM Watson generated training data (courtesy of Shreyas) identifies cats and tries to make them run towards a selected room. 

![](/img/projects/catdelivery/1.gif)

Unsurprisingly, the hardest part of this project was getting the cat to actually play with the laser pointer. A cat's apathy truly is the strongest force in the galaxy.