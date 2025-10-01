---
title: "NoisyDECOLLE: Robust Local Learning for SNNs on Neuromorphic Hardware"
authors:
- admin
- Benedikt Wahl
- Tobias Gemmeke
date: "2023-12-15"
doi: "10.1109/ICMLA58977.2023.00231"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Machine Learning and Applications (ICMLA)*
publication_short: In *ICMLA 2023*

abstract: Based on their biological archetype, spiking neural networks (SNNs) promise substantial energy savings at massively increased performance. However, best-performing SNNs in supervised learning scenarios often fall short of their potential efficiency gains as they rely on backpropagation, which entails issues like weight update locking until forward and backward passes are finished, and critical resource & computation requirements. These challenges can be tackled by drawing inspiration from biological synapses which rely largely on more local information to adapt. Local learning algorithms adopt this idea by employing local classifiers in each layer of an SNN that use only spatially and temporally local information to update synaptic weights. However, mapping these algorithms to neuromorphic systems to unleash their potential can be impaired by various kinds of noise. In this work, we review prior art to derive realistic noise scenarios on neuromorphic systems. Based on these results, we introduce NoisyDEColle, a framework for applying various noise models on locally learned SNNs using the DECOLLE network architecture. We show that both noise-aware training and additional regularization techniques allow NoisyDECOLLE to reach competitive performance, even under challenging conditions as for example posed by resistive devices. Using quantization-aware training, NoisyDECOLLE reaches 98.6% (94.1%) accuracy on N-MNIST (DVSGesture) with 3b (8b) weights (>4−10x memory and energy savings compared to 32b). To analyze our results, we provide the first time-driven implementation of spike activation maps, aiding the explainability of neuromorphic computing.

# Summary. An optional shortened abstract.
summary: NoisyDECOLLE is a Python framework for assessing the robustness of SNNs trained with local learning rules inspired by three-factor learning and synaptic plasticity.

tags:
- SNN
- Neuromorphic Computing
- Efficiency
- Robustness
featured: true

# links:
# - name: pdf
#   url_pdf: https://ieeexplore.ieee.org/abstract/document/9356357
url_pdf: https://ieeexplore.ieee.org/abstract/document/10459995
url_code: https://github.com/RWTH-IDS/noisy-decolle
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'NoisyDECOLLE example architecture'
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

