---
layout: archive
title: "Teaching"
permalink: /teaching/
---

<style>
.course-card {
  border-left: 4px solid #f0ad4e;
  background: #fffaf5;
  padding: 15px 20px;
  margin-bottom: 20px;
  border-radius: 8px;
  transition: 0.3s;
}

.course-card:hover {
  background: #fff3e6;
  transform: translateY(-2px);
}

.course-title {
  font-weight: 600;
  font-size: 16px;
}

.course-level {
  float: right;
  color: #f0ad4e;
  font-weight: 500;
}

.course-desc {
  margin-top: 5px;
  color: #555;
}
</style>

## 🎓 Teaching

{% for course in site.data.teaching %}
<div class="course-card">

  <div class="course-level">
    {{ course.level }}
  </div>

  <div class="course-title">
    {{ course.course }}
  </div>

  <div class="course-desc">
    {{ course.description }}
  </div>

</div>
{% endfor %}
