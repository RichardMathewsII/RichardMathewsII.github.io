---
layout: page
title: Resume
permalink: /resume/
weight: 4
---

<div style="text-align:center">
<h5>To request my pdf resume, please <a href="https://richardmathewsii.com/contact/"> contact</a> me.</h5></div>

{% capture list_items %}
Work Experience
Education
Projects
Skills
Extracurricular
{% endcapture %}
{% include elements/list.html title="Table of Contents" type="toc" %}

# Work Experience

<div class="row">
{% include about/experience.html %}
</div>

# Education

<div class="row">
{% include about/education.html %}
</div>

# Projects
See [projects](https://www.richardmathewsii.com/projects/)

# Skills
Check out my [project tags](https://richardmathewsii.com/projects/tags) page to see which technical skills I've demonstrated in my projects.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Technology Skills" source=site.data.other-skills %}
</div>

# Extracurricular
<div class="row">
{% include about/extracurricular.html %}
</div>