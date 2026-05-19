---
layout: page
permalink: /publications/
title: publications
description: Publications by category in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2 class="year">Journal</h2>
{% bibliography -q @*[type=journal]* %}

<h2 class="year">Conference</h2>
{% bibliography -q @*[type=conference]* %}

</div>
