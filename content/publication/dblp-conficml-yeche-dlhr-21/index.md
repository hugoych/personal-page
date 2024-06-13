---
title: Neighborhood Contrastive Learning Applied to Online Patient Monitoring
authors:
- **Hugo Yèche** *
- Gideon Dresdner *
- Francesco Locatello
- Matthias Hüser
- Gunnar Rätsch

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-01-01'
publishDate: '2024-06-12T13:23:59.484804Z'
publication_types:
- paper-conference
publication: 'In *ICML 2021*'


abstract: Intensive care units (ICU) are increasingly looking towards machine learning for methods to provide online monitoring of critically ill patients. In machine learning, online monitoring is often formulated as a supervised learning problem. Recently, contrastive learning approaches have demonstrated promising improvements over competitive supervised benchmarks. These methods rely on well-understood data augmentation techniques developed for image data which do not apply to online monitoring. In this work, we overcome this limitation by supplementing time-series data augmentation techniques with a novel contrastive learning objective which we call neighborhood contrastive learning (NCL). Our objective explicitly groups together contiguous time segments from each patient while maintaining state-specific information. Our experiments demonstrate a marked improvement over existing work applying contrastive methods to medical time-series

# Summary. An optional shortened abstract.
summary: In this work, we propose a novel contrastive learning objective, Neighborhood Contrastive Learning (NCL), designed for data exhibiting a hierarchy. We apply it to online patient monitoring tasks.                 
  
tags:
  - Self-Supervised Learning
  - Time Series

url_pdf: http://proceedings.mlr.press/v139/yeche21a.html
url_code: https://github.com/ratschlab/ncl
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

featured: true

image:
  caption: 'Illustration of the adversial objective of NCL'
  focal_point: ''
  preview_only: false

---
