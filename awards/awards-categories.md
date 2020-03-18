---
layout: landing
title: The Award Categories
description: Awards in four flavours
subtitle: Our Awards
order: 2
show_tile: false
intro: 'There are four award categories, with all entries automatically entered into
  the Cumbrian Environmental School of the Year Award.  Each award will come with a financial prize.


  Our 2020 finalists have been chosen by a panel of judges. The ultimate winners are to be voted on by Cumbrian schools over the next month.  Please have a look at some of the amazing work our environmental awards finalist schools have undertaken this year.'
permalink: "/awards/categories"
category: Award-Page
image: "/assets/images/award-montage.jpg"
nav-menu: false
button: "See the 2020 Finalists"
---
{% assign awards = site.pages | where: "category","Award" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}
