---
layout:     post
title:      "Parallax image"
subtitle:   "Parallax image effect with zoom"
date:       2015-06-05 12:31:00
author:     "Nicklas Ridewing"
header-img: "img/post-images/parallax-header.png"
---

<p>A couple of days ago I ran across a campaign site for a upcoming game title and found a cool image parallax scrolling effect that followed the mouse movement. It also used a small zoom effect once you got closer to the center of the image. This effect look really neat so I figured I give it a go myself. I started out with a single image of a forest environment which I worked out into three layers in Photoshop. A background, a middle part and a foreground.</p>

<img src="{{ site.baseurl }}/img/post-images/parallax-layers.png" alt="Parallax layers">

<p>Then I got to work on the code, I used html, css and typescript (javascript). Once I got the layers positioned with css inside a wrapper div I started working on the math in javascript to make the magic happen.</p>
