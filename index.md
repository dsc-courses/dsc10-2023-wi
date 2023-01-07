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

{: .warning } 
This site is under construction. Until this warning is removed, any content here is subject to change.

<!-- Lecture and discussion recordings can be found at [podcast.ucsd.edu](https://podcast.ucsd.edu). -->

{% for module in site.modules %}
{{ module }}
{% endfor %}