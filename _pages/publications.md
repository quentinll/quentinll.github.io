---
layout: page
permalink: /publications/
title: Publications
description: A complete list can be found on my <a href="https://scholar.google.com/citations?user=39fFsjkAAAAJ">Google Scholar</a>. #publications in reversed chronological order.
years: [2022, 2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
