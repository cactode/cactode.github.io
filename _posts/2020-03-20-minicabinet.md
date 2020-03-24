---
layout: post
title: Mini CNC Control Cabinet
subtitle: An exercise in wiring frustration
image: /img/projects/minicabinet/thumbnail.jpg
tags: [project, mechanical, software, electrical, quick build]
---
I recently saved a tiny Sherline 5040 mill from my school's dumpster. What better way to make it CNC-capable than with an equally tiny control cabinet?

The inspiration to make a tiny cabinet came after I found a tiny benchtop enclosure in my school's trash.

![](/img/projects/minicabinet/10.jpg)

I started out by CNCing holes for the DIN connectors in the front panels. Only one 1/8" endmill was lost in the process (a new record!)

![](/img/projects/minicabinet/1.jpg)

The cabinet itself hides two power supplies (one for logic, one for power), a TinyG controller, and a Raspberry Pi 3. All of these are held in place by a laser-cut acrylic skid.

![](/img/projects/minicabinet/2.jpg)

The sled is cooled by a small Noctua fan nestled in the enclosure.

![](/img/projects/minicabinet/3.jpg)

Now for the boring part of this project - wiring. A friend of mine had recently shown me his beautiful wiring cabinet from work and I was motivated to outdo him. It look longer than I'd care to admit, but it looks purty.

![](/img/projects/minicabinet/4.jpg)

Once everything was in place, it was just a matter of wrangling the wires into position.

![](/img/projects/minicabinet/5.jpg)

![](/img/projects/minicabinet/6.jpg)

The final fit was tight, but it somehow worked the first time!

![](/img/projects/minicabinet/7.jpg)

![](/img/projects/minicabinet/8.jpg)

![](/img/projects/minicabinet/9.jpg)

The final box has:
- X, Y, Z, and A axis drivers.
- Integral cooling.
- Full breakouts for limit switches, coolant, and spindle control.
- A built-in RasPi running CNCjs for control.
- Front-facing Ethernet, HDMI, and USB ports for easy debugging.

I'll post an update once I get the CNC itself running.