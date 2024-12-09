---
layout: default
title: Supplements
number: 4
---

#                                               

# Timeline

<iframe class='timeline-iframe' src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1d2ZUHFfLuLiJNU4MokBuaiMm7-97xB9yFSH6hbyQIwg&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>


# Supplementary Materials
Additional information for further research

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'EuropeStole'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'AfricaInd'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'AfricaDecolonize'" %}
{% include media.html pages=media %}
