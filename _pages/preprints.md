---
layout: page
permalink: /preprints/
title: preprints
description: Preprints and Working Papers
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015]
nav: false
showtitle: true
---

Also see:
- [All Published Works](/publications)
- [Selected Showcase Publications](/showcase)

<div class="publications by year">
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f preprints -q @*[year={{y}}]* %}
{% endfor %}

</div>