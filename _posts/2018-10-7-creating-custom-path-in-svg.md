---
layout: post
title: Creating custom path with SVG
date: 2018-10-7 20:08:12 +0300
img: 
fig-caption: 
tags: [CSS, Understanding Gender]
---

For my pet project Understanding Gender, I decided that I'm going to make the title page something like this:

> ![Main page]({{site.baseurl}}/assets/img/post/15-title-female.png)

The main page will have an animation where the skirt of the female icon will be diminishing slowly to reveal a male icon. I think this captures the gender spectrum very nicely.

> ![Main page]({{site.baseurl}}/assets/img/post/16-title-male.png)

In this case, I think the best way to do this is to create a custom SVG path and we will animate the path.

To use SVG path, we need the `<path>` element.

The commands that can be used for `<path>` element:
- M = moveto
- L = lineto
- H = horizontal lineto
- V = vertical lineto
- C = curveto
- S = smooth curveto
- Q = quadratic Bézier curve
- T = smooth quadratic Bézier curveto
- A = elliptical Arc
- Z = closepath

