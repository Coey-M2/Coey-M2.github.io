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
  - feature_row:
      - image_path: /assets/images/candle_sprite.png
        alt: "placeholder image 1"
        title: "Artwork of a pick up sprite"
        excerpt: "This is a sample piece of my artwork on sprites. This was used as an upgrade pick up for Kackle Kastle"
      - image_path: /assets/images/placeholder.png
        alt: "placeholder image 2"
        title: "Placeholder 2"
        excerpt: "This is some sample content that goes here with **Markdown** formatting"
      - image_path: /assets/images/placeholder.png
        alt: "placeholder image 3"
        title: "Placeholder 2"
        excerpt: "This is some sample content that goes here with **Markdown** formatting"
      - image_path: /assets/images/Screenshot%202026-04-30%20100524.png
        alt: "2D game level design"
        title: "2D game level design"
        excerpt: "This is my first game I created, trying my hand at a generic platformer"
      - image_path: /assets/images/placeholder.png
        alt: "placeholder image 4"
        title: "Placeholder 3"
        excerpt: "This is some sample content that goes here with **Markdown** formatting."

        feature_row:
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
