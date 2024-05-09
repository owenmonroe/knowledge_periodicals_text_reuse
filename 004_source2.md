---
layout: default
title: Section 2 Sources - Caterpillar Lace
number: 004
---


# Section 2 Sources: Caterpillar Lace

The following images are pages that include articles on caterpillar lace from _The Penny Magazine_, _The Saturday Magazine_, and _Chambers's Edninburgh Journal_. Transcripts of these pages are presented in the following page of this edition, "Section 2 Transcripts: Caterpillar Lace."

<br/><br/>


## Lace Made by Caterpillars in _The Penny Magazine_
This first image is a page from _The Penny Magazine_, June 30, 1832, issue. This is page 131 of the collected 1832 volume. 


{% assign caterpillar_penny_1 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source2'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '01'"
%}
{% include media.html pages=caterpillar_penny_1 %}

<br/><br/>



## Lace Made by Caterpillars in _The Saturday Magazine_
This image is a page from _The Saturday Magazine_, September 29, 1832, issue. This is page 139 of the collected 1832 volume. 

{% assign caterpillar_saturday_2 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source2'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '02'"
%}
{% include media.html pages=caterpillar_saturday_2 %}

<br/><br/>


## Lace Made by Caterpillars in _Chambers's Edinburgh Journal_
This image is a page from _Chambers's Edinburgh Journal_, November 9, 1833, issue. This is page 328 of the collected 1833 volume. 

{% assign caterpillar_chambers_3 = site.mindoc_media | sort: "order" |
where_exp: "item", "item.page == 'source2'" | where_exp: "item",
"item.media_type == 'image'" | where_exp: "item", "item.order == '03'"
%}
{% include media.html pages=caterpillar_chambers_3 %}





