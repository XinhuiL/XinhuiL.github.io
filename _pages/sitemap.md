---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Publications</h2>
<ul>
  {% for publication in site.publications %}
    <li>
      <a href="{{ publication.url | relative_url }}">{{ publication.title }}</a>
    </li>
  {% endfor %}
</ul>
