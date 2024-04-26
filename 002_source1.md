---
layout: default
title: The Source 1
number: 002
---

# Source 1: Mocking Bird Saturday Magazine

{% assign mockingbird_sat_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source1'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '01'"
%}
{% include media.html pages=mockingbird_sat_1 %}


# Source 2: Mocking Bird Penny Magazine

{% assign mockingbird_penny_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source1'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '02'"
%}
{% include media.html pages=mockingbird_penny_2 %}


