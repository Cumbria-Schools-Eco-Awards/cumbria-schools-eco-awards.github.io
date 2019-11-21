---
layout: landing
title: The Cumbria Eco Forum
description: Resources and events to share
subtitle: Our Forum
order: 1
nav-menu: true
permalink: "/forum"
show_tile: true
category: ''
intro: We would like to see every school in Cumbria engaged in environmental activities
  but know that starting out can be daunting. Through the eco-connections hub we want
  to link the plethora of experience available within our local community and connect
  schools to support each other. We also want to provide best case examples of initiatives
  happening across the county and create an information portal with a calendar of
  events. We will do the hard research work for you so that you can get on with the
  action.
image: '/assets/images/xr.jpg'

---
{% assign awards = site.pages | where: "category","Forum-Page" | sort: "order" %}
{% include horizontal-panels.html rows = awards %}
