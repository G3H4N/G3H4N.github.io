---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
  <li class="title-li">
        <span class="write-time"># 发表于： {{ post.date | date_to_string }} </span>
        <a class="blog-title" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
