---
layout: post
title:  "NZXT Gamma USB 3.0 Casemod"
date:   2020-05-19 14:36:46 +0100
categories: electronics EAGLE USB PCB
---
This is a write-up of a project I worked on in 2018 when this blog didn't exist.

Quite a few years ago, I decided to build my own PC; As time marched on I've 
replaced all of the components of the system at least once, except, for the case
 I originally started with.

The case is an NZXT Gamma model and in terms in I/O it came with two USB 2.0 
ports, your standard 3.5mm audio interfaces and a (doomed) eSATA port. Not 
exactly the highest-end case at the time, but I had spent all my money on the 
fun stuff like RAM and a GPU and so had very little cash left.

Fortunately, it also came with a Power Supply too! I kid, never use a power 
supply that comes with your case, just dont, please.

Rolling into 2018, I'd just gotten too lazy to reach around the back of my PC to
 plug in an external hard drive to get that sweet, sweet USB 3.0 speed 
 improvements. So, time to replace those slow boring 2.0 ports and bring this 
 case into 2008!

## What're We Working With?

With the advent of USB 3.0, four(?) new pins were added to the port meaning I'd 
have to replace the front I/O ports with fresh, shiny, new USB 3.0 compatible 
ports.

I popped open my case to get a closer look at the front I/O panel and understand 
how it's put together so I can plan how to make my high-speed USB dreams a 
reality. As I expected, all of the I/O ports are mounted to a small PCB which is 
held in position against the case with a small bracket. This part honestly 
suprised me as I was expecting the whole thing to be some free 
floating connectors hot glued into place.

I give the NZXT Gamma an "iFixit" reparability score of 9/10 because of this.
:thumbs-up:

Taking a closer look at the board, I can see that it is sensibly laid out, with 
the audio section and USB/eSATA section clearly are mounted to separate ground 
planes in order to keep the sensitive digital circuitry away from the much more 
noisy analogue audio section.

### Intel HD-Audio

I don't have any issues with the audio options that came with the case, but if
i'm going to 
