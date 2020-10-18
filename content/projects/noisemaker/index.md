---
title: "Noisemaker"
resources:
 - name: card_image
   src: images/music-waveform.jpg
 - name: megalovania
   src: audio/megalovania.mp3
 - name: frequency_modulation
   src: images/frequency-modulation.jpg
date: 2019-11
---

{{< right_image "frequency_modulation"
"Some waveforms that can be formed with frequency modulation" >}}

Noisemaker is a basic music synthesizing library written in C++. Basically, it
provides several basic modules that can control each other's input, add and
multiply outputs, and perform other basic functions. The user connects several of these
modules together, then chooses an output module to be written to a wav file. The
names of the two synthesis techniques this enables are "additive" and
"frequency modulation".

I wrote this while reading *Computer Music: Synthesis, Composition, and
Performance* by Charles Dodge, which was super interesting. The basics of how a
synthesizer works are explained, but if you're interested in exactly how these
techniques are implemented in a general purpose programming language, you may
find it informative to take a look at Noisemaker. It's open source, and you can
find it [here](https://github.com/jpear1/noisemaker).

Here's a short wobbly melody produced by Noisemaker:

{{< page_audio "megalovania" >}}
