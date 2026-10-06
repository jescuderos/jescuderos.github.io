---
layout: page
title: Publications
permalink: /publications/
nav: true
nav_order: 2
description: Journal articles, conference papers, preprints and editorial work in high-performance interconnection networks.
---

**29 journal articles · 33 peer-reviewed conference papers · 10 preprints**

Updated from my [DBLP profile](https://dblp.org/pid/72/1341.html) on **28 September 2026**, with bibliographic details checked against publisher metadata where available. All DBLP-indexed preprints are listed, including those that also have a peer-reviewed version. Browse by section and year.

Publications marked **Open Access** have an openly accessible version recorded in the bibliography, such as an arXiv version or an openly available preprint.

[Journal articles](#journal-articles) · [Conference papers](#conference-papers) · [Preprints](#preprints) · [Editorial work](#editorial-work) · [Download BibTeX]({{ '/assets/bibliography/papers.bib' | relative_url }}) · [CV]({{ '/cv/' | relative_url }})

## Journal articles

<div class="publications">

{% bibliography --query @article[keywords!=editorial] %}

</div>

## Conference papers

<div class="publications">

{% bibliography --query @inproceedings %}

</div>

## Preprints

<div class="publications">

{% bibliography --query @unpublished %}

</div>

## Editorial work

### Editorial introductions

<div class="publications">

{% bibliography --query @article[keywords=editorial] %}

</div>

### Edited proceedings

<div class="publications">

{% bibliography --query @proceedings %}

</div>
