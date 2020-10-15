---
title: "Self-Playing Guitar"
resources:
 - name: card_image
   src: images/yellow-guitar.jpg
 - name: hammer_on
   src: images/hammer-on.jpg
date: 2019-07
---

The Self-Playing Guitar, or sometimes the Air Guitar, is a project I
programmed and partially built with two other students at the Dos Pueblos
Engineering Academy in my senior year of high school.

{{< right_image "hammer_on" "A guitarist performing a hammer-on" >}}

The project is actually a lot more than just a guitar; it has a carriage of
pneumatic pistons that act as the "fingers" that play the guitar, which use a
technique called a hammer-on (when a player slams their finger down on the
string hard enough that they don't have to strum). The pistons are controlled
by an Arduino, which is in turn controlled by a Raspberry Pi, which also
controls the motor and displays the GUI.

The guitar has a library of music in MIDI format that it knows how to play. It
picks out the guitar part of the song, uses a pathfinding algorithm to figure
out how to play it efficiently, and plays the other parts using a synthesizer.
This pathfinding algorithm was written by one of my very talented teammates,
and I wrote a routine that used some music theory to simplify parts of a song
when the guitar was unable to find a way to play it.

The user can pick which song they want to hear, then once it's playing, control
the guitar in the same way they would control a music player like Spotify. They
can pause, play, stop, and fast forward/rewind. An animation of the piston and
motor movements is also displayed, as it's often difficult to see exactly what
the pistons are doing.  All of this is written in Python, using Kivy for
graphics.

My main role was writing the user interface, but because my team inherited the
unfinished guitar from older students and none of us were on the "mechanical
team", I often ended up doing some mechanical engineering too.  Using
SolidWorks, I designed things like: part of a re-imagined piston carriage,
plates to protect the electrical components from people, and plates to protect
people from the (20A, very powerful) motorized carriage. I also often
machined/laser cut such parts in our machine shop.

A point of pride for my team was our organized electrical setup. Our final
product was something like rev. 4 of the setup. We all became intimately
familiar with the smell of solder.

Here's a mini video tour of the guitar playing a couple songs, sans-synth:

{{< youtube id="b7EqSpEVfhg" autoplay="false" >}}
