---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
social: true # includes social icons at the bottom of the page
---

<!-- _pages/publications.md -->

{% if site.search_enabled %}
<input type="text" id="bibsearch" spellcheck="false" autocomplete="off" class="search bibsearch-form-input" placeholder="Type to search">
{% endif %}

<div class="publications">

{% bibliography %}

</div>
