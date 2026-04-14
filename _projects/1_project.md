---
layout: page
title: Zenji
description: A kanji learning PWA that combines AI feedback with a clean mobile-first study flow.
img: /assets/img/zenji_feedback.png
importance: 1
category: work
related_publications: false
---

# Zenji

Zenji is a kanji learning app built to make handwriting practice more interactive and less frustrating. The goal was to create a mobile-friendly study experience where users could draw characters, get feedback quickly, and keep improving without breaking flow.

## What I built

- A convolutional neural network in TensorFlow for recognizing handwritten kanji input
- A Progressive Web App experience using TypeScript and Firebase
- Real-time feedback flows that helped users understand stroke quality and character accuracy
- A production-ready team project delivered within a two-month build window

## Why it mattered

This project sat at the intersection of product design and machine learning. We needed the model to be useful, but we also needed the app to feel responsive enough that practicing characters stayed enjoyable. That balance between model quality and user experience was the most interesting part of the build.

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3 mt-md-0 ">
        {% include figure.liquid loading="eager" path="assets/img/zenji_feedback.png" title="Real-time Kanji Feedback" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A feedback view from Zenji showing how the app helped users practice and improve their kanji writing in real time.
</div>
<a href="https://zenji-1e015.web.app" target="_blank" rel="noopener noreferrer">Try Zenji now on your phone </a>
