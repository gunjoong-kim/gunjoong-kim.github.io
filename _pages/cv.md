---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download a PDF version of my CV [here](/files/cv_gunjoong.pdf).

Education
======
* **M.S. in Computer Science and Engineering**, Yonsei University, Mar. 2024 -- Feb. 2026
  * Mobile Embedded Systems Lab [lab homepage](https://mobed.yonsei.ac.kr/index.php?mid=Homepage).
  * GPA: 4.27/4.30
* **B.S. in Computer Science**, University of Seoul, Mar. 2017 -- Feb. 2024
  * GPA: 3.85/4.50, Major GPA: 4.10/4.50

Experience
======
* **Research Assistant**, Jan. 2024 -- Present
  * Mobile Embedded Systems Lab., Yonsei University, Seoul, Republic of Korea
  * **Efficient On-device AI:** Worked on advancing efficient on-device AI, exploring both model-level and system-level approaches to bridge the gap between heavy AI workloads and the limited resources of mobile devices.
  * **Immersive Computing:** Investigated system designs that support next-generation immersive applications including augmented reality and volumetric media.

Publications
======
<ul class="cv-pub-list">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Projects
======
* **viNPU: On-device Inference Optimization Framework** (2025)
  * Built a framework to run Vision Transformers efficiently on mobile NPUs by combining sensitivity-guided mixed precision with graph rewrites. Achieved average 11.5x faster inference, up to 44.9x lower energy, with near-no accuracy loss vs FP16.
  * Tools: Qualcomm Neural Processing SDK (QNN), Aimet, PyTorch, ONNX, Android

* **Vega: Mobile Volumetric Video Streaming System with 3DGS** (2024--2025)
  * Designed the first system to achieve 30 FPS full-scene volumetric video streaming on mobile devices with 3D Gaussian Splatting, reducing data size by 99% while maintaining high visual quality.
  * Tools: PyTorch, OpenGL ES, TensorFlow Lite, Qualcomm Neural Processing SDK, Android

* **ARIA: Heterogeneous Processor Acceleration for VFM Inference** (2024)
  * Developed a system for real-time VFM inference on mobile devices by combining GPU full-frame predictions with NPU dynamic-region updates, achieving 99.9% deadline success and up to 50% accuracy improvement.
  * Tools: Qualcomm AI Engine Direct SDK (QNN), LiteRT, ONNX, Android

* **Cosmos: Mobile 360 Video Streaming with Content-Aware Super-Resolution** (2024)
  * Developed a content-aware SR system for real-time 360 video streaming on mobile, sustaining 30 FPS and improving tile quality by up to 21.8%p and PSNR by 3.0 dB over prior work.
  * Tools: PyTorch, TensorFlow Lite, OpenCV, OpenGL ES, Android

Skills
======
* **Languages:** C++, C, Java, Python
* **ML Frameworks:** PyTorch, ONNX, LiteRT (TensorFlow Lite)
* **GPU/NPU Frameworks:** CUDA, OpenCL, OpenGL, Qualcomm AI Engine Direct (QNN) SDK
* **Platforms:** Android, Linux
