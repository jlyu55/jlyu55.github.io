---
title: Refining Covariance Matrix Estimation in Stochastic Gradient Descent through
  Bias Reduction
authors:
- Ziyang Wei
- Wanrong Zhu
- admin
- Wei Biao Wu
date: '2026-01-01'
publishDate: '2026-01-29T23:18:03.259819Z'
publication_types:
- article-journal
publication: '*The 29th International Conference on Artificial Intelligence and Statistics*'

abstract: We study online inference and asymptotic covariance estimation for the stochastic gradient descent (SGD) algorithm. While classical methods---such as plug-in and batch-means estimators---are available, they either require inaccessible second-order (Hessian) information or suffer from slow convergence. To address these challenges, we propose a novel, fully online de-biased covariance estimator that eliminates the need for second-order derivatives while significantly improving estimation accuracy. Our method employs a bias-reduction technique to achieve a convergence rate of {{< math >}}$n^{(\alpha-1)/2}\sqrt{\log n}${{< /math >}}, outperforming existing Hessian-free alternatives. We provide theoretical guarantees for consistency and validate the estimator's superior finite-sample performance through extensive simulations.

tags:
- Statistical Foundation of Deep Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: OpenReview
  url: https://openreview.net/forum?id=Bttn4JfaZH

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Block-based Batching Scheme for the Online Covariance Estimator'
  focal_point: ""
  preview_only: false
---
