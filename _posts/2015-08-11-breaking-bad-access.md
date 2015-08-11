---
layout: post
title: Breaking Bad Access
author: mpg
tags: uitableview selectors debugging crash
project_url: https://github.com/ProjectiveC/Breaking-Bad-Access 
---

#### What do we have:
We have a table view with food items as a list. On selecting a food item, we want to invoke ```editFood``` method but only through the ```delegateAction``` method.

<br />

#### The Problem:
On tap on any food item, it posts a notification and initiates a series of methods. This results in an exception, our very dear friend ```EXC_BAD_ACCESS```.


<br />

#### Concepts:
Broadly two concepts: debugging and troubleshooting; selectors.

For the former: we want to know the thought process behind debugging a crash, what are the main steps to trace the cause and how would this be different from tackling a ```SIGBART```.

For the latter one: a general discussion on selectors and when could we possibly want to use selector names to invoke methods.
