---
layout: about
title: about
permalink: /
description: <a href="#">Institute for Advanced Study</a>. Shenzhen University,Nanshan District Shenzhen,Guangdong,China 518060. Contacts 0755-26530611.

align: right
image: prof_pic.jpg

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
display_categories: [Prof., postdoc, former-postdoc]
---

<div class="profiles">
  <h2>Teams</h2>
  {% for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {% assign categorized_profiles = site.profiles | where: "category", category %}
  {% assign sorted_profiles = categorized_profiles | sort: "importance" %}
  <!-- Generate cards for each profiles -->
  <div class="grid">
  {% for profile in sorted_profiles %}
    {% if profile.title %}
      {% include profiles.html %}
    {% endif %}
  {% endfor %}
  </div>
  {% endfor %}
</div>
