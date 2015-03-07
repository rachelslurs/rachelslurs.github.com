---
layout: post
title: "How to Fix Webkit Text Aliasing Issues on Transitions"
date: 2015-03-07T17:05:33-05:00
reference-url: http://stackoverflow.com/a/21136111/1672670
reference-text: StackOverflow
---

If you've ever run into this issue in Safari - on transition, the text appears to go bold momentarily, and then back to a normal weight, the best solution is adding:
```css
	-webkit-font-smoothing: subpixel-antialiased;
```

The other solutions like the translateZ(0px) hack will cause the text to appear thinner.