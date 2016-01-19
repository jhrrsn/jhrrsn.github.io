---
layout: project
title:  "Floppy Blurb"
date:   2016-01-14 12:00:00
author: Jack Harrison
downloads:
- Windows: https://www.dropbox.com/s/ubf2hzesk100jtl/FloppyBlurb%20%28Windows%29.zip?dl=0
- Mac: https://www.dropbox.com/s/q5s0s7w67mfkrwr/FloppyBlurb%20%28Mac%29.zip?dl=0
categories:
- project
img: 05-floppy-blurb.png
carousel:
- 05-floppy-blurb-01.png
- 05-floppy-blurb-02.png
tagged: Game, Clone, Learning
website: https://github.com/jhrrsn/floppy-blurb
---
####FLOPPY BLURB
So, [Flappy Bird](https://en.wikipedia.org/wiki/Flappy_Bird). It's similar in a way, I suppose, to games like [Super Hexagon](http://superhexagon.com) - very challenging, _get-this-thing–through-that-gap_ action. I enjoy Super Hexagon because it's fast, testing your reactions and your ability to recognise patterns. It's also [stylish as fuck](https://www.youtube.com/watch?v=2sz0mI_6tLQ). Flappy Bird, on the other hand, isn't that fast and doesn't have much (if any) repetition in the position of the gaps you are traversing. Its challenge comes from its controls, which use an _intentionally sensitive_ physics-based system. Keeping the bird level is a challenge, and quickly adjusting height while doing so seems impossible at first.

Like [living upside down](https://en.wikipedia.org/wiki/Perceptual_adaptation), though, with repeated exposure you can eventually compensate for the challenging controls and rack up a healthy number of points. That so many people _have_ actually gone through this pain is the strangest part to me - though not all that strange really, given [our history with games](https://en.wikipedia.org/wiki/Knife_game).

Anyway, this was a quick game to make, as I could use a lot of the out-of-the-box physics features in Unity. I ran into some weirdness with the pipes; it seems that if you want your collisions to reliably trigger you need to make sure you're using a proper rigidbody on your obstacles and [moving them as a physics object](http://docs.unity3d.com/ScriptReference/Rigidbody2D.MovePosition.html) instead of just repositioning the usual way (by setting the transform). Generally, though, it was all pretty straightforward.

It's always good to finish a quick project like this one after a break, to remind yourself that you are capable of [starting & succeeding](http://jamesclear.com/start-succeed) creative work.

Onwards & upwards!
