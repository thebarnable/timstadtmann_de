---
title: "From quantitative analysis to synthesis of efficient binary neural networks"
authors:
- admin
- Cecilia Latotzke
- Tobias Gemmeke
date: "2020-12-14"
doi: "10.1109/ICMLA51294.2020.00024"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 19th IEEE International Conference on Machine Learning and Applications (ICMLA)*
publication_short: In *ICMLA 2020*

abstract: Binary Neural Networks (BNNs) offer an effective way to slash the cost of computation and memory accesses in inference. Recently, a plurality of ideas has been proposed, some of which are complementary while others are incompatible. This work presents a thorough review of state-of-the-art methods and an analysis of their computational cost based on the energy consumption of fixed-point, ternary and binary MAC vector operations. We derive an approach on how to systematically design a cost-efficient BNN. Our quantized LeNet and VGGNet architectures highlight the benefit of prudent capacity augmentation, with layer-wise ternarization providing best improvement of accuracy over μJ/classification in BNNs.

# Summary. An optional shortened abstract.
summary: We derive an approach on how to systematically design cost-efficient BNNs, with novel methods like hybrid ternarization and a hardware-based cost estimation leading to BNNs more efficient that existing ones without compromising accuracy.

tags:
- ANN
- CNN
- Efficiency
- Quantization
featured: true

# links:
# - name: pdf
#   url_pdf: https://ieeexplore.ieee.org/abstract/document/9356357
url_pdf: https://ieeexplore.ieee.org/abstract/document/9356357
url_code: https://github.com/RWTH-IDS/efficient-binary-neural-networks
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Our proposed method for systematically binarizing ANNs'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

