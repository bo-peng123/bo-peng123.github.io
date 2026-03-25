---
layout: page
permalink: /papers/
title: papers
description: Following the convention of theoretical computer science, authors are listed alphabetically.
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

<h2 class="year">Publications</h2>
{% bibliography -f papers --query @inproceedings %}
{% bibliography -f papers --query @article %}

<h2 class="year">Working Papers</h2>
{% bibliography -f papers --query @unpublished %}

</div>
