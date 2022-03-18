---
layout: page
permalink: /research/
title: research work
description: a very very short list of prepublicated research works 
years: [2021]
nav: true
---

## preprints and publications

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

---

## talks 
in construction

## additional stuff
in construction
