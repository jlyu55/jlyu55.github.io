---
title: A statistical theory of overfitting for imbalanced classification

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jingyang Lyu
- Kangjie Zhou
- Yiqiao Zhong

date: '2025-01-01'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-23T10:26:47.978519Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types:
- article-journal
# publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2502.11323*'
# publication_short: ""

abstract: "Classification with imbalanced data is a common challenge in data analysis, where certain classes (minority classes) account for a small fraction of the training data compared with other classes (majority classes). Classical statistical theory based on large-sample asymptotics and finite-sample corrections is often ineffective for high-dimensional data, leaving many overfitting phenomena in empirical machine learning unexplained. <br>In this paper, we develop a statistical theory for high-dimensional imbalanced classification by investigating support vector machines and logistic regression. We find that dimensionality induces truncation or skewing effects on the logit distribution, which we characterize via a variational problem under high-dimensional asymptotics. In particular, for linearly separable data generated from a two-component Gaussian mixture model, the logits from each class follow a normal distribution N(0,1) on the testing set, but asymptotically follow a rectified normal distribution max{κ,N(0,1)} on the training set -- which is a pervasive phenomenon we verified on tabular data, image data, and text data. This phenomenon explains why the minority class is more severely affected by overfitting. Further, we show that margin rebalancing, which incorporates class sizes into the loss function, is crucial for mitigating the accuracy drop for the minority class. Our theory also provides insights into the effects of overfitting on calibration and other uncertain quantification measures."

# Summary. An optional shortened abstract.
summary: ""

# tags:
# - Deep Learning
# - Asymptotic Theory

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://arxiv.org/abs/2502.11323

url_pdf: https://arxiv.org/pdf/2502.11323
url_code: 'https://github.com/jlyu55/Imbalanced_Classification'
url_dataset: ''
url_poster: '#'
url_project: ''
url_slides: '#'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
