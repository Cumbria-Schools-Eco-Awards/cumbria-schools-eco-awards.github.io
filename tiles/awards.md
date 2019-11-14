---
layout: landing
title: The Cumbria Eco Forum Awards
description: Awards in four flavours.
subtitle: Our Awards
order: 2
nav-menu: true
permalink: /awards
intro: Each category is open to all primary and secondary schools within Cumbria.  Each school may apply once to as many categories as they wish - excluding the innovation of year award - which will be awarded to the most innovative entrant to the other categories.
---

{% assign awards = site.pages | where: "category","Award-Page" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}
