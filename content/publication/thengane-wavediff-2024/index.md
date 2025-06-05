---
title: 'WaveDiff: Underwater Visual Data Enhancement with Wavelet-Accelerated Diffusion'
authors:
- Shrutika Vishal Thengane
- Yu Xiang Tan
- Marcel Bartholomeus Prasetyo
- Malika Meghjani
date: '2024-09-01'
publishDate: '2025-05-30T03:19:28.623675Z'
publication_types:
- paper-conference
publication: '*OCEANS 2024 - Halifax*'
doi: 10.1109/OCEANS55160.2024.10753857
abstract: Unmanned underwater vehicles generally rely on high quality visual data
  and low latency for the applications of monitoring, exploration and search. Several
  methods have been proposed to improve underwater visibility by enhancing images
  taken by cameras using generative methods such as diffusion models. Although diffusion
  models have proven very useful for visual data enhancement, they enhance images
  iteratively, making this process computationally inefficient. Current methods primarily
  focus on improving visibility without addressing operation latency or speed, rendering
  these methods unsuitable for low bandwidth or fast information tracking. To overcome
  this, we propose using discrete wavelet transform (DWT) to decompose the image into
  four frequency components, reducing the spatial dimension. Out of these four components,
  we use only one as part of the diffusion process. At the end of the diffusion process,
  we apply the inverse discrete wavelet transform to obtain the enhanced image. This
  simple strategy helps reduce processing time by 50% with minimal loss in Peak Signal
  to Noise Ratio (PSNR) and Structure Similarity Index Measure (SSIM) on the LSUI
  dataset.
tags:
- Diffusion models
- Diffusion Models
- Diffusion processes
- Discrete wavelet transforms
- Image Enhancement
- Loss measurement
- PSNR
- Sea measurements
- Time measurement
- Training
- Transforms
- Underwater Exploration
- Visual Data Enhancement
- Visualization
- Wavelet Transform
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10753857/
# - name: arXiv
#   url: https://arxiv.org/abs/2402.03636
# url_code: 'https://github.com/MARVL-Lab/MERLION'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://www.youtube.com/watch?v=LawHSlyCbsw'
---
