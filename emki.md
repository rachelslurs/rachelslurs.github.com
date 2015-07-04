---
layout: work
title: "Edward M. Kennedy Institute for the US Senate"
client: "EMKI"
permalink: emki/
tech: "Nexus 7 tablets, AngularJS, Ractive, NodeJS, Web Sockets"
press-title-1: "Edward M. Kennedy Institute Aims to Teach Collaboration"
press-link-1: "http://www.nytimes.com/2015/02/09/arts/design/edward-m-kennedy-institute-aims-to-teach-collaboration.html"
---

<iframe src="https://player.vimeo.com/video/123413904?color=c9ff23&title=0&byline=0&portrait=0" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

 - Single page web apps
 - Built with SASS, Grunt, AngularJS, Ractive.js, and vanilla JS
 - Used both standard AJAX and web sockets for cross platform communication

My favorite project was the museum which opened this year in March, which was part of Edward Kennedy’s vision for a museum to teach children about the United States Senate in an exciting and immersive way. I worked onsite in the month prior to the opening and was amazed at how empty the building appeared without our tech, with the exception of the impeccably ornate replica of the Senate chamber. The entire museum is web based: from the Android tablets each visitor uses to interact with the museum, to the enormous projections on the wall that make up most of the museum’s exhibits.

The tablets involved a considerable reliance on Angular for the various microapps contained within, and communicated with the museum at large using web sockets via Scala’s Play framework. I worked primarily on the front end for the tablets, learning a lot about Angular in the process. The wall exhibits were primarily single page web apps, but with a large reliance on responding to the states being sent by the platform. Since the animations were significant in terms of performance demands, I had to collaborate extensively with the backend engineers to come up with ways to avoid the appearance of “jank” on the front end. Most significantly, this can be seen in the exhibit “People of the Senate.” This exhibit, a single page web app, with a considerably complicated API, would change every 10 seconds for every session of the senate, going back to when there weren’t even 50 states, with pictures of each senator (or illustrations). I was tasked with adding a smooth card flip animation, even though there could be up to 50 image changes in a tick. Through some trial and error, and collaboration with the backend engineers, I created an animation that appears smooth and has an aquarium-like effect.