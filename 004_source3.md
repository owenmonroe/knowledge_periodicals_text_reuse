---
layout: default
title: The Source 3
number: 004 
---

# Source 1: Rooks Saturday Magazine 1832

{% assign rook_sat_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '01'"
%}
{% include media.html pages=rook_sat_1 %}


# Source 2: Rooks Saturday Magazine 1835

{% assign rook_sat_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '02'"
%}
{% include media.html pages=rook_sat_2 %}


# Source 3: Rooks Penny Magazine 1839, page 1

{% assign rook_penny_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '03'"
%}
{% include media.html pages=rook_penny_1 %}


# Rooks Penny Magazine 1839, page 2

{% assign rook_penny_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '04'"
%}
{% include media.html pages=rook_penny_2 %}


# Rooks Penny Magazine 1839, page 3

{% assign rook_penny_3 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '05'"
%}
{% include media.html pages=rook_penny_3 %}



