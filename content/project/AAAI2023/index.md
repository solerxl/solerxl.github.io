---
title: Efficient Top-k Feature Selection Using Coordinate Descent Method
summary: <b>Proc. <font color="red"> AAAI 2023</font></b>, **Lei Xu**, Rong Wang, Feiping Nie, Xuelong Li.
tags:
  - Conference
  - Feature Selection
date: '2023-08-22'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/solerxl/Code_For_AAAI_2023'
url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/26258'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

### Abstract

Sparse learning based feature selection has been widely investigated in recent years. In this study, we focus on the l2,0-norm based feature selection, which is effective for exact top-k feature selection but challenging to optimize. To solve the general l2,0-norm constrained problems, we novelly develop a parameter-free optimization framework based on the coordinate descend (CD) method, termed CD-LSR. Specifically, we devise a skillful conversion from the original problem to solving one continuous matrix and one discrete selection matrix. Then the nontrivial l2,0-norm constraint can be solved efficiently by solving the selection matrix with CD method. We impose the l2,0-norm on a vanilla least square regression (LSR) model for feature selection and optimize it with CD-LSR. Extensive experiments exhibit the efficiency of CD-LSR, as well as the discrimination ability of l2,0-norm to identify informative features. More importantly, the versatility of CD-LSR facilitates the applications of the l2,0-norm in more sophisticated models. Based on the competitive performance of l2,0-norm on the baseline LSR model, the satisfactory performance of its applications is reasonably expected. The source MATLAB code are available at: https://github.com/solerxl/Code_For_AAAI_2023.