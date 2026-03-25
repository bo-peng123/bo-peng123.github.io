---
layout: page
permalink: /publications/
title: papers
description: Following the convention of theoretical computer science, authors are listed alphabetically.
nav: true
nav_order: 2
---

<div class="publications">

<h2 class="year">Working Papers</h2>
{% bibliography -f papers -q @*[type=unpublished]* %}

<h2 class="year">Conference Papers</h2>
{% bibliography -f papers -q @*[type=inproceedings]* %}

<h2 class="year">Journal Papers</h2>
{% bibliography -f papers -q @*[type=article]* %}

</div>
