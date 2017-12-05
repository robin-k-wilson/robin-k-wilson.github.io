---
title: "Hi, I'm Robin."
layout: single
permalink: /example/
date: 2016-03-23T11:48:41-04:00
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/img/pragueCastle_thumbnail.jpg
  # cta_label: "Contact"
  # cta_url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "I'm a programmer and overall improver of processes. Efficiency is my middle name and I strive to fix any and all inefficiencies."
intro:
  - excerpt: 'Below are a list of my current projects.'
feature_row:
  - image_path: assets/img/robinHeadshot1_thumbnail.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/img/robinHeadshot1_thumbnail.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/img/robinHeadshot1_thumbnail.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/img/robinHeadshot1_thumbnail.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/img/robinHeadshot1_thumbnail.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/img/robinHeadshot1_thumbnail.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

[hyperlink example](https://github.com/jekyll/jekyll)



{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}