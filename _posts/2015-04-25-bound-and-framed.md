---
layout: post
title: Who Framed UILabel
tags: CGGeometry CGRect
project_url: https://github.com/ProjectiveC/BoundAndFramed
---

#### What do we have:
A UITableView of country names. Each table cell contains a single UILabel for the name.

<br />

#### The Problem:
We want the UILabel to fit the entire cell, but when we scroll down, the labels tend to disappear.

<br />

#### Concepts:
CGGeometry, more specifically the difference between _frames_ and _bounds_.