---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in page.publications reserved %}
  {% include archive-single.html %}

{% endfor %}
