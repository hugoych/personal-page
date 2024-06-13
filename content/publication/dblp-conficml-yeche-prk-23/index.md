---
title: Temporal Label Smoothing for Early Event Prediction
authors:
- Hugo Yèche *
- Alizée Pace *
- Gunnar Rätsch
- Rita Kuznetsova
date: '2023-01-01'
publishDate: '2023-03-12T13:23:59.471937Z'
publication_types:
- paper-conference
publication: '*In ICML 2023*'


abstract: 'Models that can predict the occurrence of events ahead of time with low false-alarm rates are critical to the acceptance of decision support systems in the medical community. This challenging task is typically treated as a simple binary classification, ignoring temporal dependencies between samples, whereas we propose to exploit this structure. We first introduce a common theoretical framework unifying dynamic survival analysis and early event prediction. Following an analysis of objectives from both fields, we propose Temporal Label Smoothing (TLS), a simpler, yet best-performing method that preserves prediction monotonicity over time. By focusing the objective on areas with a stronger predictive signal, TLS improves performance over all baselines on two large-scale benchmark tasks. Gains are particularly notable along clinically relevant measures, such as event recall at low false-alarm rates. TLS reduces the number of missed events by up to a factor of two over previously used approaches in early event prediction.'

summary: 'We show that by leveraging temporal dependencies in early event prediction in our objective, we can significantly improve performance over traditional MLE.'

tags:
    - Early Event Prediction
    - Regularization
    - Time Series
    
url_pdf: https://proceedings.mlr.press/v202/yeche23a.html
url_code: https://github.com/ratschlab/tls
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://slideslive.com/39003602/temporal-label-smoothing-for-early-event-prediction?ref=speaker-89235


image:
  caption: 'Illustration of the effect of TLS with stronger smoothing as we move away from the event.'
  focal_point: ''
  preview_only: false

---
