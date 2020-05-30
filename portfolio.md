---
layout: page
title: Portfolio
permalink: /portfolio/
---

<!-- 

This page is top-level view of the portfolio, going to read data from portfolio.yml and produce a list of categories, with image, etc, or potentially a featured project.

Next page down from here should be all the work within a category.

Next page down is a detail page. 

<ul>
{% for _link in site.categories %}
    <li><a href="{% if _link.external %}{{ _link.href }}{% else %}{{ _link.href | relative_url }}{% endif %}">{{ _link.text }}</a></li>
{% endfor %}
</ul>

Civic/Education

Residential

Signage and Wayfinding

Commercial -->