---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Custom header with title and button -->
<div class="d-flex justify-content-between align-items-center mb-3">
  <h1 class="page-title" style="font-size: 2.5rem; font-weight: 300;">publications</h1>
  <a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-1728-8042&sort=date%20desc%2C%20bibcode%20desc&p_=0" target="_blank" class="btn btn-secondary btn-sm">
    <i class="fas fa-external-link-alt"></i> NASA/ADS
  </a>
</div>

<!-- Hide the default title that comes from layout -->
<style>
  .page-header {
    display: none !important;
  }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <h2>first author</h2>
  {% bibliography --file firstauthor %}

  <h2>coauthor</h2>
  {% bibliography --file coauthor %}

</div>
