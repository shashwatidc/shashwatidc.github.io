---
layout: page
permalink: /code/
title: Code
description: 
nav: true
nav_order: 5
social: true # includes social icons at the bottom of the page
---
## GitHub repositories

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
