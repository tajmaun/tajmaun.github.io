---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

## Bengali Number Plate Detection Using Edge-Based and Contour-Based Methods
[[Code](https://github.com/tajmaun/Nearest-Important-Place-Visualization)]

Number plate detection plays a significant role in vehicle counting, traffic surveillance, and law enforcement. While many approaches have been proposed for detecting number plates, most focus on Latin-script plates. This thesis presents a novel and effective method for detecting Bengali number plates, addressing the challenges posed by unique script characteristics and real-world variations in plate appearance.

Our system processes generic images, including snapshots taken in natural conditions. We employ Sobel edge detection, Otsu’s thresholding, morphological closing operations, minimum bounding rectangles, and contour properties to localize the number plate. The algorithm has been successfully tested on a diverse set of real-world images.

For character recognition, we use a contour-based segmentation approach combined with a Multi-Layer Perceptron (MLP) model. Experimental results demonstrate **87%** accuracy in plate detection and **70.12%** accuracy in character segmentation, highlighting the effectiveness of our approach for Bengali number plates.

<span style="color: #0056b3;"> Grayscale Conversion    ->  Applying Gaussian Blur ->    Thresholding   ->   Morphological Operation   ->   Detected Plate </span>

<img src="/images/blur.png" alt="drawing" width="180"/>  <img src="/images/gray.png" alt="drawing" width="180"/> <img src="/images/thresholding.png" alt="drawing" width="180"/> <img src="/images/morphological_operation.png" alt="drawing" width="180"/>
<img src="/images/cropped_plate.png" alt="drawing" width="180" />



