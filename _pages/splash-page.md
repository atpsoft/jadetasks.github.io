---
title: "Happy Days!  Tasks made easy!"
layout: splash
permalink: /splash-page/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color:  "#000"
  overlay_filter: # "0.5"
  overlay_image: /assets/images/jade.png
  actions:
    - label: "Download"
      url: "https://apps.apple.com/app/apple-store/id1639946142?pt=119369382&ct=atpsoft.com&mt=8"
excerpt: 
intro: 
  - excerpt: 'Here is a few points about our task management philosophy, so you can decide if it sounds like a good fit for you. We categorize tasks first based on urgency and importance: low, medium, high. The purpose of JadeTasks is to help us accomplish not only the urgent tasks but also the myriad of tasks that are important to us but that do not have specific deadlines or urgency. We are able to accomplish this somewhat with the current version, but it is a work in progress, and expect the interface to change quite a bit over the next few months at least. We know there are plentiful to-do list apps available already with satisfied customers. But if you are not one of them, please install JadeTasks. Give it a try: offer suggestions, request features, complain about bugs. Help us make it as useful for you as it is for us. We will be listening.'
feature_row:
  - image_path: assets/images/313x0w.webp
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/313x0w.webp
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/313x0w.webp
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/313x0w.webp
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/jade.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/jade.png
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