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

{: .important } 
The first course meeting will be remote ([Zoom link here](https://ucsd.zoom.us/j/97623586285)) because Janine has Covid. Several subsequent lectures may also be remote for the same reason. Check this page for updates about when we'll be able to start in-person instruction. Thanks for your understanding!

<!-- Lecture and discussion recordings can be found at [podcast.ucsd.edu](https://podcast.ucsd.edu). -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
