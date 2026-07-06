---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <h2>First Author Publications</h2>
  {% bibliography --file firstauthor %}

  <h2>Co-authored Publications</h2>
  {% bibliography --file coauthor %}

</div>
