---
layout: post
title: "Node.js -> Go: Writing RESTful Web Services"
date: 2016-03-13 16:30
comments: true
categories: go nodejs rest talks
---

Last week, I decided to rewrite the Node.js back-end for SplitStreamr in Go. I had been meaning to get into Go for a while, so I figured rewriting something in the language would be a fairly decent first project.

When I was setting up the project, I looked at some comparisons of a bunch of web frameworks when I stumbled upon this [talk](https://www.youtube.com/watch?v=yi5A3cK1LNA) given at dotGo 2014 by Blake Mizerany. In the talk, he argues that you really don't need an extra framework or library to write RESTful web services in Go. Instead, Blake argues that `net/http`, the HTTP server built into the Go standard library, is more than sufficient. I took this to heart, and realized Blake was pretty spot on with that recommendation. Surprisingly, the typical amount of code you'd write in Go to handle an HTTP route is about the same you'd end up writing in Node.js with a framework like Express.

Flash forward to yesterday: I was watching some friends speak at Gainesville Barcamp and got inspired to put together an impromptu talk comparing writing a RESTful web service in Node.js and Express to Go.

I managed to get a bunch of Node.js folks interested in writing Go, so I'd say the talk went pretty well overall!

<script async class="speakerdeck-embed" data-id="cfef69c1015a43e38efb8e177f93fdc5" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
