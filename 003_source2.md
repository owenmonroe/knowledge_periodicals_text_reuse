---
layout: default
title: The Source 2
number: 003
---


# Source 1: Caterpillar Penny Magazine

{% assign caterpillar_penny_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source2'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '01'"
%}
{% include media.html pages=caterpillar_penny_1 %}





# Source 2: Caterpillar Saturday Magazine

{% assign caterpillar_saturday_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source2'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '02'"
%}
{% include media.html pages=caterpillar_saturday_2 %}





# Source 3: Caterpillar Chambers's Edinburgh Journal

{% assign caterpillar_chambers_3 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source2'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '03'"
%}
{% include media.html pages=caterpillar_chambers_3 %}





