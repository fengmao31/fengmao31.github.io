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
  We challenge the prevailing dogma in autonomous driving that high-performance planning necessitates high-fidelity world reconstruction. Drawing inspiration from cognitive science, we propose the Tokenized Intent World Model (TIWM). We posit that the essence of intelligence lies not in pixel-perfect reconstruction, but in the cognitive alignment between internal intent representations and physical reality. By formalizing cognitive mechanisms—sparse coding, mental simulation, and belief-intent co-evolution—into an end-to-end agentic system, we demonstrate a radical efficiency breakthrough. On NuPlan benchmarks, using only 360 scenarios (~1.5 hours, 1% of SOTA data scale), TIWM achieves an open-loop validation ADE of 0.487m (sparse activation) and 0.382m (future token prediction). In closed-loop evaluation, the agent demonstrates robust feasibility and emergent "survival instincts"—such as map affordance understanding, free exploration, and self-recovery—that transcend the boundaries of traditional imitation learning. Based on these findings, we propose two fundamental hypotheses: (1) Intelligence emerges from the consistency of attentional connectivity with the physical world, rather than mere parameter scale; (2) The Intent Token functions as the computational isomorph to the biological neural cell assembly, offering a more biologically plausible unit of computation than the artificial perceptron. This work not only bridges the gap between World Models and VLA systems but also reconciles the dichotomy between Symbolism and Connectionism, marking a pioneering engineering realization of cognitive first principles.

# Summary. An optional shortened abstract.
summary: A cognitive planning framework using sparse intent tokens. TIWM achieves emergent survival behaviors and exceptional data efficiency without requiring high-fidelity world reconstruction.

tags:
- AI

featured: true

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: '#'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://youtu.be/I6rIkOuZOFY'

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

{{< youtube I6rIkOuZOFY >}}

Old version:

https://arxiv.org/abs/2511.05540

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
