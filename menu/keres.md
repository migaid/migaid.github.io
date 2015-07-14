---
layout:      page
sidebar:     right
breadcrumb:  true

title:       "Keresés"
subheadline: "Keress az oldalon a Google segítségével"
teaser:      "Írd be a lenti szövegdobozba a keresett szót vagy kifejezést, és nyomd meg az entert!"
permalink:   "/keres/"
header:
   image_fullwidth: "header.jpg"
   
---


{% include google_search.html %}

<form style="padding-bottom: 200px;" onsubmit="google_search()" >
  <input type="text" id="google-search" placeholder="{{ site.data.language.enter_search_term }}">
</form>
