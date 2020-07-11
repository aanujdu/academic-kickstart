---
title: "BoMaNet: Boolean Masking of an Entire Neural Network"
authors:
- admin
- Rosario Cammarota
- Aydin Aysu
date: "2020-06-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *STC*

abstract:Recent work on stealing machine learning (ML) models from inference engines with physical side-channel attacks warrant an urgent need for effective side-channel defenses. This work proposes the first fully-masked neural network inference engine design. Masking uses secure multi-party computation to split the secrets into random shares and to decorrelate the statistical relation of secret-dependent computations to side-channels (e.g., the power draw). In this work, we construct secure hardware primitives to mask all the linear and non-linear operations in a neural network. We address the challenge of masking integer addition by converting each addition into a sequence of XOR and AND gates and by augmenting Trichina's secure Boolean masking style. We improve the traditional Trichina's AND gates by adding pipelining elements for better glitch-resistance and we architect the whole design to sustain a throughput of 1 masked addition per cycle. We implement the proposed secure inference engine on a Xilinx Spartan-6 (XC6SLX75) FPGA. The results show that masking incurs an overhead of 3.5\% in latency and 5.9× in area. Finally, we demonstrate the security of the masked design with 2M traces.


# Summary. An optional shortened abstract.
summary: This paper proposes the hardware design and implementation of a neural network classifier resistant to power-based side-channel attacks using gate-level Boolean masking.

tags:
- Source Themes
featured: true

links:
- name: Link
  url: https://arxiv.org/abs/2006.09532
url_pdf: https://arxiv.org/abs/2006.09532.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

