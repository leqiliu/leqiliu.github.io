---
layout: page
permalink: /publications/
title: Publications
description:  <b> * </b> denotes equal contribution
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<div class="alert alert-warning" role="alert" style="margin-bottom: 2rem; padding: 1rem; background-color:rgb(250, 247, 236); border: 1px solid #ffc107; border-radius: 0.25rem;">
  <strong>This page will no longer be updated. For my latest publications and preprints, please refer to <a href="https://scholar.google.com/citations?user=zmbW4iUAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener noreferrer">Google Scholar</a>.</strong>
</div>

<h1> Preprints </h1>
{% bibliography -f papers -q @*[category=preprint]%}

<h1> Publications </h1>
{% bibliography -f papers -q @*[category!=preprint]%}

</div>

