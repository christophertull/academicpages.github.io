---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [__my Google Scholar profile__](https://scholar.google.com/citations?user=_XLutrUAAAAJ&hl=en)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
