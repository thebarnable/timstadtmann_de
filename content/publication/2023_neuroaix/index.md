---
title: "neuroAIx: FPGA cluster for reproducible and accelerated neuroscience simulations of SNNs"
authors:
- admin
- Kevin Kauth
- Vida Sobhani
- Tobias Gemmeke
date: "2023-10-23"
doi: "10.1109/NorCAS58970.2023.10305473"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE Nordic Circuits and Systems Conference (NorCAS)*
publication_short: In *NorCAS 2023*

abstract: The complex mechanisms and impressive learning capabilities of the human brain inspire the search for ever more efficient neural network models. Investigating the specific nature of biological neural networks in accelerated simulations with hundreds of millions of synapses, however, pushes even the most sophisticated systems to their limits. At the same time, the inherent chaotic nature of spiking networks and their typically distributed simulation complicates reproducibility, which is a major concern in both research and engineering. With HPC systems incrementally surpassing biological real-time in the simulation of neuroscience networks of significant size and complexity, novel computing architectures are required to reach disruptive speed-ups while assuring determinism and providing flexibility for continuous adaptations to new insights from neuroscience.To this end, we developed the neuroAIx FPGA cluster, based on off-the-shelf AMD/Xilinx FPGAs. It integrates a proprietary ultra-low-latency communication architecture and a custom short-range synchronization algorithm that brings worst-case source-to-destination spike latency down to 2 microseconds. Together with a latency-hiding memory-prefetch procedure, it enables deterministic simulations of the widely-used cortical microcircuit model, with nearly 80k neurons and 300M synapses, with an acceleration factor of 20x compared to biological real-time. This surpasses all existing systems, outperforming non-FPGA platforms by 10x, while providing the flexibility needed to explore neuro-inspired algorithms in the future.

# Summary. An optional shortened abstract.
#summary: 

tags:
- FPGA
- Embedded Software
- Xilinx
- Neuroscience
- Neuromorphic Computing
- Performance
- Efficiency
featured: true

# links:
# - name: pdf
#   url_pdf: https://ieeexplore.ieee.org/abstract/document/9356357
url_pdf: https://ieeexplore.ieee.org/abstract/document/10305473
url_code: https://github.com/RWTH-IDS/neuroAIx-perf-sim
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'neuroAIx outperforms existing accelerators in performance and efficiency'
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

