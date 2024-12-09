---
layout: default
title: Credits
number: 6
---

# Credits and Acknowledgments

Introduction, Website by Evan Weinzimer

Analysis One of French Colonialism in Africa by Jackson McCarthy

Analysis Two of British Colonialism in Africa by Reilly Jordan

Analysis Three of the Belgian Colonialism in The Congo by Brett Biddle 

Conclusion, Timeline, Supplementary Materials, by Valentina Salazar

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'AfriqueCake'" %}
{% include media.html pages=media %}
