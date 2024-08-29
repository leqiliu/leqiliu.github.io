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
<h1> Preprints </h1>
{% bibliography -f papers -q @*[category=preprint]%}

<h1> Publications </h1>
{% bibliography -f papers -q @*[category!=preprint]%}

</div>

