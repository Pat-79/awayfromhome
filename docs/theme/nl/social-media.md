---
title: Social Media
layout: page
lang: nl
ref: page-social-media
image: /assets/images/pages/photos/Golden_Gate_by_patrickske.webp
permalink: /nl/social-media/
---

Deze sectie is nog in opbouw. Nieuwe social media-links worden hier binnenkort toegevoegd.

{% include social-links.html class_name='social-links social-links--drawer' %}

## YouTube

Video's die ik op YouTube heb geplaatst zijn te bekijken op mijn [YouTube-kanaal](https://www.youtube.com/@-Away-From-Home-)

{% include video-widget.html
  provider="youtube"
  youtube_id="CIWgifiybWk"
  aspect_ratio="16:9"
  controls="true"
  privacy_mode="true"
  max_width="720px"
%}

## Instagram

Volg me op mijn [Instagram-account](https://www.instagram.com/awayfromhome_nl/), waar ik korte snaps deel van waar ik ook ben!

## Fotogalerij

Je hebt misschien gemerkt dat elke pagina en blogpost zijn eigen hero-afbeelding heeft. Dit zijn geen stockfoto's, maar foto's die ik door de jaren heen tijdens mijn reizen heb gemaakt.

Ik heb alle foto's voor je gebundeld in een galerij:

{% include gallery-widget.html
  src="/assets/images/pages/photos/"
  mode="carousel"
  show_caption="false"
  autoplay_seconds="5"
  min_width="50vw"
  min_height="50vh"
  max_width="720px"
  align="center"
%}

## Video montage

Op de homepage laat ik een video montage zien van plekken waar ik ben geweest. Net zoals bij de foto's, is elk video fragment door mezelf opgenomen vanaf plaatsen overal op de wereld.

{% include video-widget.html
  provider="hls"
  src="/assets/streams/home-title-v2/home-title.m3u8"
  poster="/assets/images/pages/photos/Turtle_Bonaire_by_Patrickske.webp"
  min_width="50vw"
  max_width="900px"
  aspect_ratio="16:9"
  autoplay="true"
  muted="true"
  loop="false"
  controls="true"
%}