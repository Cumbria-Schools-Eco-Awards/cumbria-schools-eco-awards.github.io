---
layout: awards
title: The Award Categories
description: Awards in four flavours.
subtitle: Our Awards
order: 2
show_tile: true
intro: Each category is open to all primary and secondary schools within Cumbria.  Each
  school may apply once to as many categories as they wish - excluding the innovation
  of year award - which will be awarded to the most innovative entrant to the other
  categories.
permalink: "/awards/categories"
category: Award
image: "/assets/images/pic09.jpg"
nav-menu: true

---
{% assign awards = site.pages | where: "category","Award" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}