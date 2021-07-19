---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.co.in/citations?user=yymAYRoAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Color code: Orange: journal, <span style="color:green">Green</span>: conference, Purple: workshop.