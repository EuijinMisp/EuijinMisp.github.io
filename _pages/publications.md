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

## Journal Articles

{% bibliography --query @article --group_by none %}

## Conference Proceedings

{% bibliography --query @inproceedings --group_by none %}

</div>
