---
layout: page
description: Information about RADIUSS mission, products, and DevOps.
title: About
permalink: /about/
graph: true
---


## What is RADIUSS?

{% include radiuss/about.html %}

<div class="row" style="padding-top:20px; flex-direction:row">
    <div class="col-md-12" style="flex-direction:row">
    {% include graphs/languages.html width=410 height=410 %}<span style="padding-left:50px">
    {% include graphs/licenses.html width=300 height=200 %}
    </span>
    </div>
</div>

## RADIUSS Products

{% include radiuss/products.html %}

<div class="row" style="padding-top:20px; flex-direction:row">
    <div class="col-md-12">
    {% include graphs/topics.html width=800px height=400px %}
    </div>
</div>


## DevOps for HPC

{% include radiuss/rse-ops.html %}
