---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Published Papers

{% for post in site.publications reversed %}
  {% unless post.title contains "Bridging social structure" or post.title contains "Quantifying compositionality" %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

## Papers Under Review

{% for post in site.publications reversed %}
  {% if post.title contains "Quantifying compositionality" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Papers in Preparation

{% for post in site.publications reversed %}
  {% if post.title contains "Bridging social structure" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

