---
layout: landing
title: The Cumbria Eco Forum
description: We would like to see every school in Cumbria engaged in environmental
  activities but know that starting out can be daunting. Through the eco-connections
  hub we want to link the plethora of experience available within our local community,
  connect schools to support each other, provide best case examples of initiatives
  happening across the county, create an information portal and a calendar of events.
  We will do the hard research work for you so that you can get on with the action.
subtitle: Our Forum
order: 1
nav-menu: true
permalink: "/forum"
show_tile: true
category: ''
intro: Recourses and events to share
image: ''

---
{% assign awards = site.pages | where: "category","Forum-Page" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}