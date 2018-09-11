---
layout: post
title:  "My Personal Mobility Data 2015"
date:   2018-09-10 10:00:00 +0200
author: David
keywords: data, mobility
category: lab
image: /img/photo-1491118217331-c147f566d809.jpeg
description: Here is presented my mobility digital traces over the last year...
---

Here is presented my mobility digital traces over the last year.

First, I wanted to extract a power law of activities durations, where the top left chart represents activities in term of duration.

In terms of space, I wanted to represent the total destinations that I visited across the year, where there three clusters, which are linked in a spation temporal scale. From the main cluster, that’s where my daily activity occurs, therefore, urban traces come to live, showing up my personal city, where I work, live, etc.

In the temporal side the daily gyration radius [1] was calculated, in order to have sense of daily activities throughout the year. Burst of activity can be appreciated, which exceed my average daily mobility and can be linked to certain periods of times over the year.

![](https://cdn-images-1.medium.com/max/3612/1*8sbnoEuzBo8w-bp6vu7n_g.png)

All the data was collected with a [Flask](http://flask.pocoo.org/) application which has granted access to my Google fit data.

References:

1. [Marta C. González, César A. Hidalgo, and Albert-László Barábasi. Understanding individual human mobility patterns, June 7, 2008.](https://www.nature.com/articles/nature06958)