---
title: "BAIT: A Blur Aware Inertial-fused Trajectory
Prediction pipeline for Autonomous Driving"
date: 2026-06-01
weight: 1
tags: ["autonomous driving", "trajectory prediction", "motion blur", "multimodal sensor fusion", "IMU", "ADAS"]
author: ["Aswinkumar Varathakumaran", "Nirmala Paramanandham"]
description: "A blur-aware multi-sensor trajectory prediction framework combining camera-based blur detection, inertial measurements, and a Residual Transformer-LSTM architecture for autonomous driving."
summary: "BAIT is a blur-aware inertial-fused trajectory prediction framework that flags visually degraded frames and adapts forecasting by combining camera-based blur detection, IMU measurements, and external agent motion cues. Using a Residual Transformer and Dual-Stream Multi-Scale LSTM encoder, it achieves the lowest error at the 6s horizon (minADE of 0.97 m and minFDE of 2.06 m) and the lowest minFDE across all horizons on the nuScenes Mini split."
cover:
    image: "BAIT_Cover_Image.png"
    alt: "BAIT Paper"
    relative: true
# editPost:
#     URL: "https://github.com/pmichaillat/hugo-website"
#     Text: "Source"
---

---

##### Download

+ [Paper](BAIT_Trajectory_Prediction.pdf)
+ [Code]()
+ [Data](https://www.nuscenes.org/)

---

##### Abstract

The visually impaired face severe mobility challenges due to reduced spatial awareness and limited real-time environmental understanding. Traditional aids such as white canes or guide dogs provide only local, static information and do not convey dynamic obstacle movement or path structure. This paper introduces PROXI-NAV, an embedded navigation assistance system that leverages a multi-head YOLOv8 architecture with monocular depth estimation to provide continuous auditory guidance. The system runs on an NVIDIA Jetson Nano, performing obstacle detection, pavement segmentation, and lightweight depth estimation in real time. Audio cues are generated from spatial reasoning over detected obstacles and depth maps, enabling safe, adaptive navigation through cluttered environments. Experimental evaluations demonstrate the system's ability to generate low-latency, context-aware navigation instructions, outperforming traditional sequential pipelines by reducing latency and improving user situational awareness.

---

##### Figure 1: System Architecture (placeholder)

![](arch_diag.png)

---

##### Citation

Varathakumaran, A., Jawahar, A., Mynampati, S., Sajidha, S. A., & Thaseen, S. (2025). *PROXI-NAV: Proximity-Aware Navigation with Audio-Visual Sensing Intelligence*. Procedia Computer Science, FTNCT08.

```latex
@inproceedings{Varathakumaran2025ProxiNav,
  author    = {Aswinkumar Varathakumaran and Akshita Jawahar and Sreya Mynampati and Sajidha S A and Sumaiya Thaseen},
  title     = {PROXI{-}NAV: Proximity{-}Aware Navigation with Audio{-}Visual Sensing Intelligence},
  booktitle = {Procedia Computer Science, FTNCT08},
  year      = {2025},
  url       = {https://YOUR_LINK_HERE}
}