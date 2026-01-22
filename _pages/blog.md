---
layout: default
permalink: /blog/
title: academic ancestor tree
nav: true
nav_order: 1
pagination:
  enabled: true
  collection: posts
  permalink: /page/:num/
  per_page: 5
  sort_field: date
  sort_reverse: true
  trail:
    before: 1 # The number of links before the current page
    after: 3 # The number of links after the current page
---

<div class="mb-5">
  <p class="lead">I'm very lucky to trace a mentorship line from Gottfried Leibniz all the way to my own doctoral advisors.</p>
  <figure class="figure w-100 text-center">
    <img src="{{ '/assets/img/academic-ancestor.png' | relative_url }}" alt="Academic ancestor tree illustration" class="figure-img img-fluid rounded shadow-sm">
    <figcaption class="figure-caption text-muted">Academic lineage from Leibniz to Zhijin Guo, inspired by the classical supervisor tree.</figcaption>
  </figure>
</div>
