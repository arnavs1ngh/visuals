---
layout: post
title:  "Monte Carlo Pi estimations 3D"
date:   2020-04-15
thumbnail: frame-2.png
dependencies:
    - p5
---

It is often convenient to split a complex javascript file in different files.
In this case, make sure to import all the files:

{%highlight html %}
<div id="sketch-holder">
    <script type="text/javascript" src="sketch/Particle.js"></script>
    <script type="text/javascript" src="sketch/ParticleSystem.js"></script>
    <script type="text/javascript" src="sketch/sketch.js"></script>
</div>
{% endhighlight %}

This particle system is [one of p5.js official examples](https://p5js.org/examples/simulate-particle-system.html):
<div id="sketch-holder">
    <script type="text/javascript" src="sketch/sketch.js"></script>
</div>