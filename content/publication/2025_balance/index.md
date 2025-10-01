---
title: "Balanced and Efficient Spiking Neural Networks"
authors:
- admin
- Janek Paessens
- Tobias Gemmeke
date: "2025-07-03"
#doi: "10.1109/ICMLA58977.2023.00231"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE 2025 International Joint Conference on Neural Networks (IJCNN)*
publication_short: In *IJCNN 2025*

abstract: Spiking Neural Networks promise an efficient and robust alternative to traditional Artificial Neural Networks. When compared to the human brain, however, they are far from achieving their full potential, the reason unclear so far. Recent neuroscience research offers a clue to solve this puzzle - tight balance. The excitatory and inhibitory input currents flowing into individual neurons have been observed to be balanced very tightly on a millisecond scale. This substantially exceeds the traditional E/I balance that is established on population level. Accompanying theoretical works have shown that spiking networks operating in this tight regime can implement more efficient and robust codes in their spike trains. In this work, we consolidate these theoretical insights with modern neuromorphic computing approaches to apply them to complex classification problems. We show up to 99.9% reductions in firing rates in balanced networks compared to unbalanced ones on the neuroscience-inspired cue-based navigation task, and outperform prior work by achieving 97.60% accuracy. The resulting approach can easily be mapped to neuromorphic hardware as its core relies on a balanced initialization scheme only. Moreover, even complex variants only involve adaptions of neuron and synapse models. Ultimately, our work shows the importance of integrating novel insights from neuroscience research into modern spiking networks to increase their efficiency and robustness using neuromorphic methods.

# Summary. An optional shortened abstract.
summary: Translating novel insights from computational neuroscience into neuromorphic computing, we show how tightly balanced Spiking Neural Networks outperform existing networks in efficiency, robustness while maintaining competitive accuracy. 

tags:
- SNN
- Neuromorphic Computing
- Balance
- Efficiency
- Robustness
featured: true

# links:
# - name: pdf
#   url_pdf: https://ieeexplore.ieee.org/abstract/document/9356357
# url_pdf: https://ieeexplore.ieee.org/abstract/document/10459995
url_code: https://github.com/RWTH-IDS/bsnn
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Correlation of efficiency, accuracy and balance'
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

