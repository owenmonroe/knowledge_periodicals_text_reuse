---
layout: default
title: The Source 1
number: 002
---

# Source 1: Mocking Bird Saturday Magazine Page 1

{% assign mockingbird_sat_1 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" %}
{% include media.html pages=mockingbird_sat_1 %}

