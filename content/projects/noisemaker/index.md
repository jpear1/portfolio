---
title: "Noisemaker"
resources:
 - name: card_image
   src: images/music-waveform.jpg
 - name: megalovania
   src: audio/megalovania.mp3
date: 2019-11
---

Noisemaker is a basic music synthesizer written in C++. It's capable of
additive and frequency modulation synthesis techniques. I wrote this while
reading *Computer Music: Synthesis, Composition, and Performance* by Charles
Dodge, which was super interesting. If you're at all interested in digital
synthesis, I'd recommend taking a look at it. The basics of how a synthesizer
works are explained, but if you're interested in exactly how these techniqutes
are implemented in a general purpose programming language, you may find it
informative to take a look at Noisemaker. It's open source, and you can find it
[here](https://github.com/jpear1/noisemaker).

Here's a short wobbly melody produced by Noisemaker:

{{< page_audio "megalovania" >}}
