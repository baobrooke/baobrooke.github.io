---
layout: page
permalink: /resources/
title: resources
description: Curated list of recommended readings, media, websites, and more.
nav: true
nav_order: 4
---

## Readings

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for item in site.data.resources.readings %}
    {% include repository/resource_item.liquid item=item %}
  {% endfor %}
</div>

---

## Movies & Documentaries

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for item in site.data.resources.movies %}
    {% include repository/resource_item.liquid item=item %}
  {% endfor %}
</div>

---

## Websites & Tools

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for item in site.data.resources.websites %}
    {% include repository/resource_item.liquid item=item %}
  {% endfor %}
</div>

---

## Newsletters, Blogs & Substacks

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for item in site.data.resources.newsletters %}
    {% include repository/resource_item.liquid item=item %}
  {% endfor %}
</div>

---

## Other Recommendations

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for item in site.data.resources.misc %}
    {% include repository/resource_item.liquid item=item %}
  {% endfor %}
</div>
