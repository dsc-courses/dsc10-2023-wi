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

{: .note }
**This is the website of a previous offering of DSC 10. To see the most recent offering, go to [dsc10.com](https://dsc10.com), and to see other DSC course websites, go to [dsc-courses.github.io](https://dsc-courses.github.io).**

<!-- Lecture and discussion recordings can be found at [podcast.ucsd.edu](https://podcast.ucsd.edu). -->

<!-- [Jump to the current week](#week-10){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
