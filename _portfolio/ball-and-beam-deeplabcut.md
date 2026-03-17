---
title: "Ball and Beam Motion Analysis Using DeepLabCut"
collection: portfolio
excerpt: "Computer vision-based extraction of angular position and angular velocity from experimental videos.<br/><img src='/images/bab_dlc_test.png' style='margin-top:5px;'>"
share: false
---
<p>
  <img src="/images/Video_BAB.gif" style="margin-top:30px;">
</p>

This project focuses on the extraction of kinematic variables from experimental videos of a Ball and Beam system using DeepLabCut and Python-based post-processing tools. The workflow combines markerless pose estimation, geometric reconstruction and signal processing techniques to estimate angular position and angular velocity from video recordings.  

The main objective is to obtain experimental motion data from visual information in order to support modeling, validation and analysis of dynamic systems.

Main steps of the workflow include:

- video preprocessing and conversion
- markerless keypoint tracking using DeepLabCut
- geometric reconstruction of beam angle
- filtering and smoothing of the estimated signal
- angular velocity estimation from reconstructed motion data

Tools and technologies:

- Python
- DeepLabCut
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- SciPy

This repository contains notebooks and source code for the full analysis pipeline. Raw videos and intermediate outputs are not included due to file size limitations.

[Repository](https://github.com/EdoAlmeida/ball-and-beam-dlc)
