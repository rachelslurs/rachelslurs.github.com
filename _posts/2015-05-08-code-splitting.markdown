---
layout: post
title: code splitting
date: 2015-05-08 11:28
url: http://webpack.github.io/docs/code-splitting.html
---

[code splitting](http://webpack.github.io/docs/code-splitting.html)

> For big web apps it’s not efficient to put all code into a single file, especially if some blocks of code are only required under some circumstances. webpack has a feature to split your codebase into “chunks” which are loaded on demand. Some other bundlers call them “layers”, “rollups”, or “fragments”. This feature is called “code splitting”.
> 
> It’s an opt-in feature. You can define split points in your code base. webpack takes care of the dependencies, output files and runtime stuff.
> 
> To clarify a common misunderstanding: Code Splitting is not just about extracting common code into a shared chunk. The more notable feature is that Code Splitting can be used to split code into an on demand loaded chunk. This can keep the initial download small and downloads code on demand when requested by the application.

