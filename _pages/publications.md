---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- Add a button at the top -->
<div style="text-align: center; margin-bottom: 20px;">
  <a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-1728-8042&sort=date%20desc%2C%20bibcode%20desc&p_=0" target="_blank" class="btn btn-secondary">
    <i class="fas fa-external-link-alt"></i> NASA/ADS
  </a>
</div>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <h2>first author</h2>
  {% bibliography --file firstauthor %}

  <h2>coauthor</h2>
  {% bibliography --file coauthor %}

</div>
