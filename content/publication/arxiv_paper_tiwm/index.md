---
title: "Token Is All You Need: Cognitive Planning through Belief–Intent Co-Evolution"
authors:
- Shiyao Sang
date: "2025-03-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: ""

abstract: | 
  We challenge the prevailing philosophical assumption that high-performance autonomous driving necessitates high-fidelity world reconstruction. Drawing inspiration from cognitive science, we propose the Tokenized Intent World Model (TIWM). We posit that the essence of intelligence lies not in pixel-perfect reconstruction, but in the cognitive alignment between the internal intent world and physical reality. We successfully formalize cognitive mechanisms—sparse coding, mental simulation and belief-intent co-evolution—into an end-to-end agentic system. In NuPlan benchmarks, using only 360 scenarios (approx. 1.5 hours, 11,000+ frames)—merely 1% of the data scale used by SOTA methods—our model achieves an open-loop validation ADE of 0.487m via sparse activation, and 0.382m with future token prediction. In closed-loop evaluation, it attains a score of 59. Crucially, the agent exhibits cognitive behaviors in simulation, such as map affordance understanding, free exploration without navigation, and robust recovery strategies. These "survival instincts" transcend the boundaries of traditional imitation learning. Based on these findings, we propose two fundamental hypotheses: (1) Intelligence is determined by the consistency of attentional connectivity with the physical world, rather than merely by parameter count or data volume; (2) The Token functions as the computational isomorph to the biological neural cell assembly (functional neuron), rather than the artificial perceptron. Our work not only bridges the engineering gap between World Models and VLA systems but also reconciles the dichotomy between Symbolism and Connectionism, marking a pioneering engineering realization of cognitive science principles.

# Summary. An optional shortened abstract.
summary: We introduce the Tokenized Intent World Model (TIWM), a paradigm shift that challenges the necessity of high-fidelity world reconstruction. By formalizing Tokens as functional neural cell assemblies, our agent achieves a closed-loop score of 59.24 on NuPlan using only 1% of the data required by SOTA methods (score 89.87). This work demonstrates state-of-the-art data efficiency, bridging the gap between World Models and VLA systems and reconciling the dichotomy between Symbolism and Connectionism.

tags:
- AI

featured: true

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: 'https://github.com/fengmao31/fengmao31.github.io/blob/main/content/publication/thesis_education_robot/ieeeconf_rimaos2c_draft.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
# - robotaxi

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

Old version:

https://arxiv.org/abs/2511.05540

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
