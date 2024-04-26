---
layout: default
title: The Source 1
number: 002
---

# Source 1: Mocking Bird Saturday Magazine Page 1

{% assign mockingbird_sat_1 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | "item.order == '01'" %}
{% include media.html pages=mockingbird_sat_1 %}


# Mocking Bird Saturday Magazine Page 2

{% assign mockingbird_sat_2 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '02'" %}
{% include media.html pages=mockingbird_sat_2 %}



# Source 2: Mocking Bird Penny Magazine Page 1

{% assign mockingbird_penny_1 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '03'" %}
{% include media.html pages=mockingbird_penny_1 %}


# Mocking Bird Penny Magazine Page 2

{% assign mockingbird_penny_2 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '04'" %}
{% include media.html pages=mockingbird_penny_2 %}
