---
layout: page
permalink: /publications/
title: Publications
description: >
  Publications by categories in reversed chronological order.<br>
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<p>
  <span class="badge" style="background-color: #c506cc; color: white;">LSC</span> Logistics & Supply Chain Management;
  <span class="badge" style="background-color: #22bda1; color: white;">AgriFood</span> Sustainable Food and Agricultural Systems;
  <span class="badge" style="background-color: #b5651d; color: white;">RSTrans</span> Resilient & Safe Transportation Infrastructure.
</p>
<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

<style>
  /* Bold my name instead of underline */
  .publications ol.bibliography li .author em {
    border-bottom: none !important;
    text-decoration: none !important;
    font-style: normal;
    font-weight: bold;
  }

  /* Badge text colors */
  .abbr .badge[style*="#c506cc"] div { color: #ffffff !important; }  /* LSC */
  .abbr .badge[style*="#22bda1"] div { color: #ffffff !important; }  /* AgriFood */
  .abbr .badge[style*="#b5651d"] div { color: #ffffff !important; }  /* RSTrans */
</style>
