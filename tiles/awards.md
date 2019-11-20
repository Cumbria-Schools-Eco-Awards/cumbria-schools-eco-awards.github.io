---
layout: landing
title: The Cumbria Eco Forum Awards
description: Awards in four flavours
subtitle: Our Awards
order: 2
nav-menu: true
permalink: "/awards"
intro: There is currently no requirement for schools to engage in environmental initiatives
  and despite this, we know there are countless examples of school groups taking action
  to protect the planet and minimise our impact on it. These initiatives are often
  reliant on the motivation and altruism of staff and students. We will be giving
  Cumbrian schools a chance to showcase what they are doing to improve environmentalism
  and sustainability, be rewarded for them.
show_tile: true
image: ''
category: ''

---
{% assign awards = site.pages | where: "category","Award-Page" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}