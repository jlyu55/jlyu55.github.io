---
title: A Statistical Theory of Overfitting for Imbalanced Classification
authors:
- admin
- Kangjie Zhou
- Yiqiao Zhong
date: '2026-01-01'
publishDate: '2026-01-29T23:18:03.253793Z'
publication_types:
- article-journal
publication: '*The Fourteenth International Conference on Learning Representations*'

abstract: Classification with imbalanced data is a common challenge in machine learning, where minority classes form only a small fraction of the training samples. Classical theory, relying on large-sample asymptotics and finite-sample corrections, is often ineffective in high dimensions, leaving many overfitting phenomena unexplained. In this paper, we develop a statistical theory for high-dimensional imbalanced linear classification, showing that dimensionality induces truncation or skewing effects on the logit distribution, which we characterize via a variational problem. For linearly separable Gaussian mixtures, logits follow {{< math >}}$\mathsf{N}(0, 1)${{< /math >}} on the test set but converge to {{< math >}}$\max\{\kappa, \mathsf{N}(0, 1)\}${{< /math >}} on the training set---a pervasive phenomenon we confirm on tabular, image, and text data. This phenomenon explains why the minority class is more severely affected by overfitting. We further show that margin rebalancing mitigates minority accuracy drop and provide theoretical insights into calibration and uncertainty quantification.

# Summary. An optional shortened abstract.
summary: "Overfitting in high-dimensional imbalanced classification arises from truncation/skewing effects on the logit distribution."

tags:
- Statistical Foundation of Deep Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2502.11323
- name: OpenReview
  url: https://openreview.net/forum?id=cKthi6QfUr

url_pdf: ''
url_code: 'https://github.com/jlyu55/Imbalanced_Classification'
url_dataset: ''
url_poster: 'poster.pdf'
url_project: ''
url_slides: 'Slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Empirical Logit Distribution (ELD) and Testing Logit Distribution (TLD)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
