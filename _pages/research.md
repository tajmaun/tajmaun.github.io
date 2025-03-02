---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

## Number Plate Detection Using Edge-Based and Contour-Based Methods
Number plate detection is a crucial application in vehicle counting, traffic surveillance, and law enforcement. Over the years, numerous algorithms and techniques have been proposed to address this problem. This thesis presents a novel and straightforward approach for detecting number plates in real-world scenarios. Our system is designed to work with generic images, including snapshots captured under realistic conditions.

Our method utilizes Sobel edge detection, Otsu’s thresholding, morphological closing operations, minimum bounding rectangles, and contour properties to accurately localize number plates. The algorithm has been successfully tested on a variety of real-world images.

For character recognition, we employed a contour-based segmentation approach alongside a Multi-Layer Perceptron (MLP) model. Experimental results demonstrate an **87%** accuracy in plate detection and **70.12%** accuracy in character segmentation, highlighting the effectiveness of our approach.

## Image Gallery

**Grayscale Conversion    ->  Applying Gaussian Blur ->    Thresholding   ->   Morphological Operation   ->   Detected Plate**  
<img src="/images/blur.png" alt="drawing" width="180"/>  <img src="/images/gray.png" alt="drawing" width="180"/> <img src="/images/thresholding.png" alt="drawing" width="180"/> <img src="/images/morphological_operation.png" alt="drawing" width="180"/>
<img src="/images/cropped_plate.png" alt="drawing" width="180" />



