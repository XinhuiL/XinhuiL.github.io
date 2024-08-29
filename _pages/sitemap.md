---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

You could use the following link to quickly find the content you are interested in!

<h2>Publications</h2>
<ul>
  {% for publication in site.publications %}
    <li>
      <a href="{{ publication.url | relative_url }}">{{ publication.title }}</a>
    </li>
  {% endfor %}
</ul>
