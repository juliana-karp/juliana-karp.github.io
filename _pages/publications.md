---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Position the button to the right of the existing title -->
<div style="position: relative;">
  <div style="position: absolute; right: 0; top: -2.5rem;">
    <a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-1728-8042&sort=date%20desc%2C%20bibcode%20desc&p_=0" target="_blank" class="btn btn-secondary btn-sm">
      <i class="fas fa-external-link-alt"></i> NASA/ADS
    </a>
  </div>
</div>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <h2>first author</h2>
  {% bibliography --file firstauthor %}

  <h2>coauthor</h2>
  {% bibliography --file coauthor %}

</div>
