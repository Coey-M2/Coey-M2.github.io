---
title: "Home page"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/house_dream.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/11C2aoYulrqvwsTtjHroPBPl9XvqUr834/view?usp=sharing"
      target: "_blank"

excerpt: "This is my portfolio website dedicated to showing of my works and achievements"

intro:
  - excerpt: "Below is some images of work I have done during my time as a game design and development student in Ulster"
  -feature_row:
  - image_path: /assets/images/Coin%20bag%20pick%20up%20sprite.png
    alt: "Coin bag"
    title: "Coin bag"
    excerpt: "This is artwork example that i have done during my first year"
  - image_path: /assets/images/Armour_sprite.png
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is artwork example that i have done during my first year"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/candle_sprite.png
    alt: "placeholder image 4"
    title: "Placeholder 3"
    excerpt: "This is artwork example that i have done during my first year"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
