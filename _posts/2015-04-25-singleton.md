---
layout: post
title: Living Singleton
tags: design-patterns singleton gcd
project_url: https://github.com/ProjectiveC/Singleton
---


#### What do we have:
A singleton class where we can initialise a string pattern. We then call a singleton function that doubles the pattern before printing it on console.

<br />

#### The Problem:
Instead of a string pattern, the console prints ```(null)```.

<br />

#### Concepts:
Who hasn't faced a question about design patterns in an interview? This problem can be followed after a general enquiry about the common design patterns. As most people have the singleton code memorised, we can ask the candidate to write the alternate code snippet for ```dispatch_once```, even strike up with a discussion about GCD functions.