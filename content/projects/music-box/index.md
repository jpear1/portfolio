---
title: "Programmable Music Box"
resources:
 - name: card_image
   src: images/music-box-doodle.jpg
 - name: bare_music_box
   src: images/bare-music-box.jpg
date: 2019-06
---

The programmable music box is a project I wrote software for at the Dos
Pueblos Engineering academy in my senior year of high school with one other
student.

{{< right_image "bare_music_box" "A bare music box" >}}

Normal music boxes are built so that each columns of pins can only play one
note.  This is because the tines that are plucked by each column have a fixed
length.

The programmable music box allows users to create their own tune on a music
box. The holes in the rotating drum have magnets at their bottom, so people can
simply drop the provided metal pins into these holes, set the drum spinning,
then listen to the song they've created.

Users can also program the "tines" (actually just metal detectors) so that they
play different instruments and notes.

The music box was built by other students, but like the [self-playing guitar],
I programmed the UI, which ran on a Raspberry Pi, and my fellow programmer
hooked up a slave Arduino to the metal detectors and synthesizer.

Here's a video of the mid-development music box in action:

{{< youtube id="H15YcX_hRQI" >}}

[self-playing guitar]: </projects/guitar>
