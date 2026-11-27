---
layout: archive
permalink: /people/
title: "People"
excerpt: "Current and previous students"
author_profile: true
---

{% include base_path %}

{% assign categories = "phd|PhD Students,intern|Master's & Bachelor's Students,project|Student Projects" | split: "," %}

{% for group in site.data.people %}
  {% assign group_name = group[0] %}
  {% assign members = group[1] %}
  {% if members and members.size > 0 %}
  {% if group_name == "current" %}<h2>Current Students</h2>{% else %}<h2>Previous Students</h2>{% endif %}
  {% for cat in categories %}
    {% assign c = cat | split: "|" %}
    {% assign people = members | where: "category", c[0] %}
    {% if people.size > 0 %}
    {% if group_name == "current" and c[0] == "phd" %}{% assign show_photo = true %}{% else %}{% assign show_photo = false %}{% endif %}
<h3>{{ c[1] }}</h3>
<div class="people-grid">
  {% for person in people %}{% include person-card.html person=person show_photo=show_photo %}{% endfor %}
</div>
    {% endif %}
  {% endfor %}
  {% endif %}
{% endfor %}
