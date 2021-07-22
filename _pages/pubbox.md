---
title: "Pubbox"
layout: gridlay
sitemap: false
author_profile: true
permalink: /pubbox/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

## Pubbox

<!-- <div class="jumbotron"> -->
<!-- ### Preprints -->
<!-- {% bibliography --query @unpublished %} -->
<!-- </div> -->

<div class="jumbotron">
### Refereed journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Refereed conference proceedings
{% bibliography --query @inproceedings %}
</div>

<div class="jumbotron">
### Other publications
{% bibliography --query @thesis,@report %}
</div>

