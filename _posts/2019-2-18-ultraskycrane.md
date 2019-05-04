---
layout: post
title: Ultra Skycrane
subtitle: A building-sized whipped cream dispenser
image: /img/projects/ultraskycrane/thumbnail.jpg
tags: [project, electrical, mechanical, software, quick build]
---
![](/img/projects/ultraskycrane/1.jpg)

It's big.

![](/img/projects/ultraskycrane/2.jpg)

_Very_ big.

![](/img/projects/ultraskycrane/3.gif)

This is a building-sized (60ft by 20ft) cartesian motion platform that... sprays whipped cream on people.

![](/img/projects/ultraskycrane/4.gif)

A couple of friends and I built this for MakeMIT, a hardware hackathon held at MIT. Since this was my last year participating as a student, I decided to try the most ridiculous idea I could think of. I had previously built an [oversized crane](/2018-11-01-skycrane) for a different hackathon, but I wanted something more. I wanted _bigger_. Specifically, I wanted something as large as the hacking space was. A cartesian motion platform seemed like a natural choice.

But how do you make linear rails long enough for something like this? Stiffness falls with the cube of length, so any unsupported rail for this would have to be prohibitively thick. The answer: rope.

![](/img/projects/ultraskycrane/5.jpg)

Specifically, climbing rope under 200lb of tension. The idea is based off of the principle of [tensegrity](https://en.wikipedia.org/wiki/Tensegrity); by putting the ropes under high tension, they can be turned into extremely stiff rails upon which a gantry/carriage can run.

![](/img/projects/ultraskycrane/6.jpg)

Leightweight aluminum carriages ride on the ropes and provide pulleys for a basic CoreXY motion setup.

![](/img/projects/ultraskycrane/7.jpg)

Motion is provided by a hyper-scaled CoreXY system using fishing line and capstan drives. The preload for the capstans comes from the sag of the ropes!

![](/img/projects/ultraskycrane/8.jpg)

The actual carriage isn't much to look at, but the payload that hangs on it...

![](/img/projects/ultraskycrane/9.jpg)

...is an IOT whipped-cream dispenser. IOT? Why? There's no way of getting wires to the whipped-cream dispenser, so it actually operates wirelessly by means of a battery pack and a small RPi Zero running a python script. 

![](/img/projects/ultraskycrane/10.gif)

All for this.

