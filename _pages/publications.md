---
layout: archive
title: "Publications"
permalink: /publications/
---

## 📄 Selected Publications

<ul>
{% for pub in site.data.publications %}
  <li>
    <strong>{{ pub.title }}</strong><br>
    {{ pub.authors }}<br>
    <em>{{ pub.journal }}</em>, {{ pub.year }}
  </li>
  <br>
{% endfor %}
</ul>
