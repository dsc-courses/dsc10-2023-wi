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
Friday's lecture will be **remote** ([Zoom link here](https://ucsd.zoom.us/j/97623586285)) because Janine still has Covid. Monday is a holiday, and we'll almost certainly be able to start in-person instruction on Wednesday. 

<!-- Lecture and discussion recordings can be found at [podcast.ucsd.edu](https://podcast.ucsd.edu). -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
