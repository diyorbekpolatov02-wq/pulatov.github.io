---
layout: archive
title: "Publications"
permalink: /publications/
---

<style>
.year-title {
  font-size: 22px;
  margin-top: 30px;
  border-bottom: 2px solid #ddd;
  padding-bottom: 5px;
}

.pub-card {
  border-left: 4px solid #2c7be5;
  background: #f9fbfd;
  padding: 15px 20px;
  margin: 15px 0;
  border-radius: 8px;
  transition: 0.3s;
}

.pub-card:hover {
  background: #eef5ff;
}

.pub-title {
  font-weight: 600;
}

.pub-authors {
  color: #555;
}

.pub-journal {
  font-style: italic;
  color: #2c7be5;
}

.pub-links a {
  margin-right: 10px;
  text-decoration: none;
  color: #007bff;
  font-weight: 500;
}
</style>

## 📄 Publications

{% assign grouped = site.data.publications | group_by: "year" | sort: "name" | reverse %}

{% for year in grouped %}
  <div class="year-title">{{ year.name }}</div>

  {% for pub in year.items %}
    <div class="pub-card">

      <div class="pub-title">{{ pub.title }}</div>

      <div class="pub-authors">{{ pub.authors }}</div>

      <div class="pub-journal">{{ pub.journal }}</div>

      <div class="pub-links">
        {% if pub.pdf %}
          <a href="{{ pub.pdf }}">📄 PDF</a>
        {% endif %}
        {% if pub.doi %}
          <a href="{{ pub.doi }}">🔗 DOI</a>
        {% endif %}
      </div>

    </div>
  {% endfor %}

{% endfor %}
