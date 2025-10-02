---
title: "neuroAIx-Framework: design of future neuroscience simulation systems"
authors:
- Kevin Kauth
- admin
- Vida Sobhani
- Tobias Gemmeke
date: "2023-04-20"
doi: "10.3389/fncom.2023.1144143"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Frontiers in Computational Neuroscience*
publication_short: In *Frontiers in Computational Neuroscience*

abstract: Research in the field of computational neuroscience relies on highly capable simulation platforms. With real-time capabilities surpassed for established models like the cortical microcircuit, it is time to conceive next-generation systems - neuroscience simulators providing significant acceleration, even for larger networks with natural density, biologically plausible multi-compartment models and the modeling of long-term and structural plasticity. Stressing the need for agility to adapt to new concepts or findings in the domain of neuroscience, we have developed the neuroAIx-Framework consisting of an empirical modeling tool, a virtual prototype, and a cluster of FPGA boards. This framework is designed to support and accelerate the continuous development of such platforms driven by new insights in neuroscience. Based on design space explorations using this framework, we devised and realized an FPGA cluster consisting of 35 NetFPGA SUME boards. This system functions as an evaluation platform for our framework. At the same time, it resulted in a fully deterministic neuroscience simulation system surpassing the state of the art in both performance and energy efficiency. It is capable of simulating the microcircuit with 20× acceleration compared to biological real-time and achieves an energy efficiency of 48nJ per synaptic event.


# Summary. An optional shortened abstract.
summary: The neuroAIx framework is a collection of C++-based simulation tools and hardware platforms to evaluate novel hardware concepts for neuroscience experiment accelerators.

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
url_pdf: https://publications.rwth-aachen.de/record/958610/files/958610.pdf
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

