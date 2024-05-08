---
layout: default
title: The Source 1
number: 002
---

# Section 1 Sources: The Mocking Bird

The following images are pages that include articles on the mocking bird from _The Saturday Magazine_ and _The Penny Magazine_. Transcripts of these pages are presented in the following webpage "Section 1 Transcripts: The Mocking Bird"
<br/><br/> 

## The Mocking Bird in _The Saturday Magazine_
The first two images are consecutive pages from _The Saturday Magazine_ July 13, 1833, issue. These are pages 15 - 16 of the collected 1833 volume. 




{% assign mockingbird_sat_1 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '01'" %}
{% include media.html pages=mockingbird_sat_1 %}





{% assign mockingbird_sat_2 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '02'" %}
{% include media.html pages=mockingbird_sat_2 %}





<br/><br/> 
## The Mocking Bird in _The Penny Magazine_
The next three images are consecutive pages from the November 16, 1833, issue of _The Penny Magazine_, pages 443 – 445 in the collected 1833 volume. The third page celebrates industrial child labor in the article "A Well-Conducted Factory." 




{% assign mockingbird_penny_1 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '03'" %}
{% include media.html pages=mockingbird_penny_1 %}





{% assign mockingbird_penny_2 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '04'" %}
{% include media.html pages=mockingbird_penny_2 %}




{% assign mockingbird_penny_3 = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source1'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '05'" %}
{% include media.html pages=mockingbird_penny_3 %}



