---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our projects bridge cutting-edge analytical science with urgent biomedical challenges. Current research includes investigating functional antibodies in SARS-CoV-2 infection and vaccination, identifying novel biomarkers and molecular insights for ARDS-induced lung injury and IgA nepropahthy, sepsis-induced acute kidney injury, oral verrucous hyperplasia, etc. Across all projects, we combine advanced mass spectrometry workflows with multi-omics and systems biology approaches to translate molecular discoveries into clinical insights.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
