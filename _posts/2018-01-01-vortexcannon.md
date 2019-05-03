---
layout: post
title: Automatic Face Tracking Vortex Cannon
subtitle: Kids these days...
image: /img/projects/vortexcannon/thumbnail.jpg
tags: [project]
---

I made a vortex cannon when I was around 12. It was a trash bag taped to a cardboard box with a few rubber bands holding it taught. Shooting rings of air at my parents was a favorite hobby of mine until they eventually stomped it to pieces. I deserved it, but the legacy of that cardboard box deserves to be honored.


A vortex cannon works by pushing a precise volume of air through a properly sized orfice. The faster you push the air, the faster the ring travels. How do you push a precise amount of air as fast as possible? A subwoofer! Or two. A subwoofer is electric, so you might as well automate the process. Ooo, and mount it on a gimbal. With cameras.

![](/img/projects/vortexcannon/1.png)

This was all theory; if the math is off, the whole thing won't work. A few weeks were needed for me to research vortex formation theory; research papers from Microsoft proved to be particularly useful. But eventually, one CAD later, I had a design.

![](/img/projects/vortexcannon/2.jpg)

![](/img/projects/vortexcannon/3.jpg)

![](/img/projects/vortexcannon/4.jpg)

80/20, waterjet aluminum, and hobby servos are the building blocks of this machine. 1/2" aluninum plate was somehow the only stock I could find. No kill like overkill...

![](/img/projects/vortexcannon/5.jpg)

![](/img/projects/vortexcannon/6.jpg)

![](/img/projects/vortexcannon/7.jpg)

A gimbal requires two axis of rotation. The bottom swivel needed a lazy susan of some kind, but I couldn't find any that would last; I ended up making a lazy susan from scratch. The other pivot was handled with regular bearings.

![](/img/projects/vortexcannon/8.jpg)

The orfice size was calculated using the Slug Theory of vortex formation. The Microsoft papers provided some additional guidance on optimization.

![](/img/projects/vortexcannon/9.jpg)

![](/img/projects/vortexcannon/10.jpg)

![](/img/projects/vortexcannon/11.jpg)

Turbulence within the vortex cannon's body degrades the system's performance, so a wrapped-polycarbonate design was used to minimize sharp edges.

![](/img/projects/vortexcannon/12.jpg)

![](/img/projects/vortexcannon/13.jpg)

![](/img/projects/vortexcannon/14.jpg)

I didn't want to use gears to couple the servos to the gimbal because modeling proper involute gears in Solidworks is a pain in the butt. A capstan drive (with electrical wire as cable) made for a good substitute.

![](/img/projects/vortexcannon/15.jpg)

![](/img/projects/vortexcannon/16.jpg)

![](/img/projects/vortexcannon/17.jpg)

As is tradition, the electronics were imprisoned in the base. A massive 1000W amplifier was recruited to power the subwoofers. A Raspberry Pi was stuck in the base to act as the brains.

![](/img/projects/vortexcannon/18.jpg)

![](/img/projects/vortexcannon/19.jpg)

After slapping a camera on the cannon body, the cannon could be assembled.

![](/img/projects/vortexcannon/20.jpg)

![](/img/projects/vortexcannon/21.jpg)

The capstan drive also came together here. The springs are needed to maintain tension; the cubic friction only works when tension isn't zero!


OpenCV (with Haar Cascades) was used for face detection. A simple PD controller was written to aim the gimbal at any faces it could find. Once a face was locked on, the Raspberry Pi could be commanded to send a short pulsing waveform to the subwoofers.

![](/img/projects/vortexcannon/22.jpg)

The machine worked beautifully! I demoed it at XFair (a career fair held by TechX) and watched as it peppered passarby with invisible vortex rings. My parents can't smash this one.