---
layout: landing
title: The Award Categories
nav-menu: true
description: Awards in four flavours.
intro: Each category is open to all primary and secondary schools within Cumbria.  Each school may apply once to as many categories as they wish - excluding the innovation of year award - which will be awarded to the most innovative entrant to the other categories.
order: 2
---
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Our Awards</h2>
		</header>
		{{ page.intro }}
	</div>
</section>


{% assign awards = site.pages | where: "category","Award" | sort: "order" %}
<section id="two" class="spotlights">
  {% for award in awards %}
    <section>
      <a href="{{ award.url }}" class="image">
        <img src="{{ award.image }}" alt="" data-position="center center" />
      </a>
      <div class="content">
        <div class="inner">
          <header class="major">
            <h3>{{ award.title }}</h3>
          </header>
          <p>{{ award.content }}</p>
          <ul class="actions">
            <li><a href="{{ award.url }}" class="button">Learn more</a></li>
          </ul>
        </div>
      </div>
    </section>
  {% endfor %}
</section>
