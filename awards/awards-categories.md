---
layout: landing
title: The Award Categories
description: Awards in four flavours
subtitle: Our Awards
order: 2
show_tile: false
intro: 'There are four award categories, with all entries automatically entered into
  the Cumbrian Environmental School of the Year Award. Our winners will be chosen
  by a panel of judges (yet to be announced). Each award will come with a financial
  prize. '
permalink: "/awards/categories"
category: Award-Page
image: "/assets/images/award-montage.jpg"
nav-menu: false

---
{% assign awards = site.pages | where: "category","Award" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}