---
layout: page
title: Portfolio
permalink: /portfolio/
---

<!-- 

This page is top-level view of the portfolio, going to read data from portfolio.yml and produce a list of categories, with image, etc, or potentially a featured project.

Next page down from here should be all the work within a category.

Next page down is a detail page. 


Civic/Education

Residential

Signage and Wayfinding

Commercial -->
Hi-

<ul>
{% for blarg in site.categories[page.tag] %}
    <li><a href="{{site.url}}/{{blarg.tag}}">{{blarg.tag}}</a></li>
{% endfor %}
</ul>

