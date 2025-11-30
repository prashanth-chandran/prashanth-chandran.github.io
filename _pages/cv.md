---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
<div class="cv-list">
{% for item in site.data.cv.work %}
  {% include cv-item.html item=item %}
{% endfor %}
</div>

Internships
======
<div class="cv-list">
{% for item in site.data.cv.internships %}
  {% include cv-item.html item=item %}
{% endfor %}
</div>

Education
======
<div class="cv-list">
{% for item in site.data.cv.education %}
  {% include cv-item.html item=item %}
{% endfor %}
</div>

Skills
======
{% for category in site.data.cv.skills %}
* **{{ category.category }}**: {{ category.items }}
{% endfor %}

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
  <ul>{% for post in site.patents reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
