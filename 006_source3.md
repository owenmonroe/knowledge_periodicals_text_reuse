---
layout: default
title: Section 3 Sources - Rooks
number: 006
---

# Section 3 Sources: Rooks
The following images are pages that include articles on rooks from _The Saturday Magazine_, and _The Penny Magazine_. Transcripts of these pages are presented in the following page of this edition, ["Section 3 Transcripts: Rooks."](https://owenmonroe.github.io/knowledge_periodicals_text_reuse/007_transcripts3.html)
<br/><br/>


## Rooks in _The Saturday Magazine_
This first image is a page of _The Saturday Magazine_, August 11, 1832 issue. This is page 56 of the collected 1832 volume. 

{% assign rook_sat_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '01'"
%}
{% include media.html pages=rook_sat_1 %}

<br/><br/>

This images is a page of _The Saturday Magazine_, the July 25, 1835, issue. This is page 31 of the collected 1835 volume.

{% assign rook_sat_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '02'"
%}
{% include media.html pages=rook_sat_2 %}


<br/><br/>



## Rooks in _The Penny Magazine_ 

The following three images are consecutive pages of _The Penny Magazine_, the December 31, 1838, monthly supplement issue. These are pages 33 – 35 of the 1839 collected volume.

{% assign rook_penny_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '03'"
%}
{% include media.html pages=rook_penny_1 %}



{% assign rook_penny_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '04'"
%}
{% include media.html pages=rook_penny_2 %}




{% assign rook_penny_3 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source3'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '05'"
%}
{% include media.html pages=rook_penny_3 %}






