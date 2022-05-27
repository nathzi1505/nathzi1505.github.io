---
layout: page
permalink: /publications/
title: Publications
description: Humble contributions to advance scientific thought and experimentation
years: [2022, 2021, Under Review]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">&nbsp;</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
