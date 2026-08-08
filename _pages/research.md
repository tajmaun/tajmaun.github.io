---
layout: archive
title: "Research"
permalink: /research/
excerpt: "Applied research in computer vision, wearable systems, and human-computer interaction."
author_profile: true
show_title: false
---

<p class="page-kicker">Research</p>
# Applied inquiry, measurable systems impact

<p class="page-intro">My research interests connect computer vision, wearable interaction, and systems performance. I am drawn to work that can be evaluated rigorously and translated into useful technology.</p>

<p class="eyebrow">Undergraduate thesis · Computer vision</p>
## Bengali number plate detection

Bengali-script number plates introduce distinctive character shapes and real-world variation that are not addressed well by methods designed primarily for Latin-script plates. This thesis developed and evaluated a detection and segmentation pipeline for generic images captured in natural conditions.

<ul class="tag-list"><li>Computer vision</li><li>Image processing</li><li>Sobel edges</li><li>Otsu thresholding</li><li>MLP</li></ul>

<div class="stats-grid" aria-label="Research results">
  <div class="stat-card"><strong>87%</strong><span>plate-detection accuracy</span></div>
  <div class="stat-card"><strong>70.12%</strong><span>character-segmentation accuracy</span></div>
  <div class="stat-card"><strong>5 stages</strong><span>in the localization pipeline</span></div>
</div>

The system combines Sobel edge detection, Otsu thresholding, morphological closing, minimum bounding rectangles, and contour properties to localize a plate. Character recognition uses contour-based segmentation with a multi-layer perceptron model.

<div class="research-visual">
  <div class="process-grid">
    <figure class="process-step"><img src="/images/gray.png" alt="Input converted to grayscale"><figcaption>1 · Grayscale</figcaption></figure>
    <figure class="process-step"><img src="/images/blur.png" alt="Gaussian blur applied to the image"><figcaption>2 · Gaussian blur</figcaption></figure>
    <figure class="process-step"><img src="/images/thresholding.png" alt="Thresholded number plate image"><figcaption>3 · Thresholding</figcaption></figure>
    <figure class="process-step"><img src="/images/morphological_operation.png" alt="Image after morphological operations"><figcaption>4 · Morphology</figcaption></figure>
    <figure class="process-step"><img src="/images/cropped_plate.png" alt="Localized and cropped Bengali number plate"><figcaption>5 · Detected plate</figcaption></figure>
  </div>
</div>

<div class="button-row">
  <a class="button-link" href="https://github.com/tajmaun/Number-Plate-Detection/tree/master/bengali_number_plate_detection">View source code</a>
  <a class="button-link button-link--ghost" href="/files/Thesis_11205028.pdf">Read thesis</a>
</div>

## Current research direction

<div class="card-grid">
  <article class="content-card"><h3>Wearable interaction</h3><p>Reducing cognitive effort and making small-screen, context-aware interactions feel more natural.</p></article>
  <article class="content-card"><h3>System performance</h3><p>Finding architectural opportunities—such as parallel pre-loading—to improve constrained-device responsiveness.</p></article>
  <article class="content-card"><h3>Gesture interfaces</h3><p>Exploring smart-ring gesture recognition as an input method for controlling nearby devices.</p></article>
</div>
