---
layout: post
title: I'm on Top of The Scroll
author: mpg
tags: uitableview scroll
project_url: https://github.com/ProjectiveC/NoScrollToTop 
---

#### What do we have:
We have a calendar-esque view. In this single view app, we have name of the days on the top as header and date as a table just below the header.

<br />

#### The Problem:
This view has 30 rows in table and a header on the top of the list/view. iOS users tend to touch the status bar to scroll the view to the top. This functionality is broken here.

<br />

#### Concepts:
The scrollsToTop property of the UIScrollView, handling mutiple scrolls on one view.


<br />

#### References:
* [UIScrollView: scrollsToTop property](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIScrollView_Class/index.html#//apple_ref/occ/instp/UIScrollView/scrollsToTop)
