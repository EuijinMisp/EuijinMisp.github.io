---
layout: page
permalink: /publications/
title: publications
description: Journal and conference publications, grouped by type in reversed chronological order.
nav: true
nav_order: 2
toc:
  sidebar: left
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Journal Articles</h2>

{% bibliography --query @article --group_by none %}

<h2>Conference Proceedings</h2>

{% bibliography --query @inproceedings --group_by none %}

</div>
