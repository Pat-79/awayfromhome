---
title: Social Media
layout: page
lang: en
ref: page-social-media
image: /assets/images/pages/photos/Golden_Gate_by_patrickske.webp
permalink: /social-media/
redirect_from: /en/social-media/
---

This section is still under construction. New social media links will be added here.

{% include social-links.html class_name='social-links social-links--drawer' %}

## YouTube

Videos uploaded to YouTube can be watched on my [YouTube channel](https://www.youtube.com/@-Away-From-Home-)

{% include video-widget.html
  provider="youtube"
  youtube_id="CIWgifiybWk"
  aspect_ratio="16:9"
  controls="true"
  privacy_mode="true"
  max_width="720px"
%}

## Instagram

Follwo me on my [Instagram account](https://www.instagram.com/awayfromhome_nl/), I will post quick snapshots from  whereever I am!

## Photo gallery

You might have noticed that each page and blogpost has its own Hero image. These photos are not stock images, but were taken during my travels during the years.

I've compiled every photo into a gallery for you to view:

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

At the homepage I show a video montage of places I have been. Just like with the photos, every clip of the video montage was recorded by myself from places all over the world.

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