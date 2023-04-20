---
layout: archive
title: Tips and Tricks
permalink: /tips/
author_profile: true
redirect_from:
  - /tricks/
description: "Tips, tricks and useful librairies for programming."
---

<h3>{{ page.description }}</h3>

{% include base_path %}

<br>
 
 --- 
{% for post in site.tips %}
  {% include archive-single-tips.html %}
 --- 
{% endfor %}

<!-- <ul>
    {% for post in site.tips %}
        <li>
            <h3 class="post-title">
                <a href="{{ post.url }}">
                    {{ post.title }}
                </a>
            </h3>
        </li>
    {% endfor %}
</ul> -->