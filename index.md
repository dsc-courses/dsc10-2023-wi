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

{{: .warning }} Make sure to fill out the [End of Quarter Survey](https://forms.gle/pmorTbJ18ufDBeiq8) + [CAPEs](https://cape.ucsd.edu/) before Saturday at 8am. If we reach an 80% response rate on both surveys, everyone will get an extra 0.5% extra credit on their overall grade!

<!-- Lecture and discussion recordings can be found at [podcast.ucsd.edu](https://podcast.ucsd.edu). -->

[Jump to the current week](#week-10){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}
