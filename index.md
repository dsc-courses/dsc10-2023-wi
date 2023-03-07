---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

<!-- Lecture and discussion recordings can be found at [podcast.ucsd.edu](https://podcast.ucsd.edu). -->

[Jump to the current week](#week-9){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}
