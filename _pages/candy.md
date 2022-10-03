---
title: "Candy"
layout: splash
permalink: /candy/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/candy-ke-header.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: ""Normal stuff. Nice life, cool flat, fun job. Someone to watch movies with.""
intro: 
  - excerpt: "Collection of what I love."
feature_row:
  - image_path: assets/images/candy-book.jpg
    alt: "Villanelle reading 'How to get over your ex in 10 steps'"
    title: "Books"
    excerpt: "Feminism, fantasy, political economy, weird stories, etc."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/candy-movie.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Some movies"
    title: "Movies"
    excerpt: "Films, anime, TV plays, etc."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/candy-music.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: ""
    title: "Music"
    excerpt: "Yico, disco, etc."
feature_row2:
  - image_path: /assets/images/candy-food-keseason1.jpg
    alt: "the night they met for the first time."
    title: "I just want to have dinner with you."
    excerpt: "All kinds of food I enjoy."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}