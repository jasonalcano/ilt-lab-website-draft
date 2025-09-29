---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

 We are a multidisciplinary team of scientists, students, and collaborators dedicated to pushing the boundaries of analytical and translational research using multi-omics and systems biology. Principal investigators and clinicians collaborate and work closely alongside with graduate students and research staff to develop new methodologies, analyze complex datasets, and apply our findings to real-world biomedical problems.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/bg-1.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

<p><h2>Alumni</h2></p>
{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
