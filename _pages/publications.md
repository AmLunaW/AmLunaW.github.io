---
layout: page
permalink: /publications/
title: Publications
description: >
  Publications by categories in reversed chronological order.<br>
  <span class="badge" style="background-color: #00369f; color: white;">LSC</span> Logistics & Supply Chain Management;
  <span class="badge" style="background-color: #22bda1; color: black;">AgriFood</span> Sustainable Food and Agricultural Systems;
  <span class="badge" style="background-color: #b5651d; color: white;">RSTrans</span> Resilient & Safe Transportation Infrastructure.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

<style>
  .publications ol.bibliography li .author em {
    border-bottom: none !important;
    text-decoration: none !important;
    font-style: normal;
    font-weight: bold;
  }
</style>
