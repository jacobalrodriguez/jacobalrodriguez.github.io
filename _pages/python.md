---
title: "Python"
permalink: /python/
header:
  image: "/images/mainheader.jpg"
---

Coming Soon.

{{ content }}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for python in site.category.python %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}