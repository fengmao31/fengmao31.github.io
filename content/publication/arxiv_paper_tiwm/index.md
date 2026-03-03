---
title: "Constructing the Umwelt: Cognitive Planning through Belief-Intent Co-Evolution"
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
  This paper challenges a prevailing epistemological assumption in End-to-End Autonomous Driving: that high-performance planning necessitates high-fidelity world reconstruction. Inspired by cognitive science, we propose the Mental Bayesian Causal World Model (MBCWM) and instantiate it as the Tokenized Intent World Model (TIWM), a novel cognitive computing architecture. Its core philosophy posits that intelligence emerges not from pixel-level objective fidelity, but from the Cognitive Consistency between the agent’s internal intentional world and physical reality. By synthesizing von Uexküll’s Umwelt theory, the neural assembly hypothesis, and the triple causal model (integrating symbolic deduction, probabilistic induction, and force dynamics) into an end-to-end embodied planning system, we demonstrate the feasibility of this paradigm on the nuPlan benchmark. Experimental results in open-loop validation confirm that our Belief-Intent Co-Evolution mechanism effectively enhances planning performance. Crucially, in closed-loop simulations, the system exhibits emergent human-like cognitive behaviors, including map affordance understanding, free exploration, and self-recovery strategies. We identify Cognitive Consistency as the core learning mechanism: during long-term training, belief (state understanding) and intent (future prediction) spontaneously form a self-organizing equilibrium through implicit computational replay, achieving semantic alignment between internal representations and physical world affordances. Based on this, we propose two fundamental hypotheses: (H1) The efficacy of embodied intelligence depends less on parameter scale or data volume, and more on the degree of semantic alignment between internal attentional dynamics and physical affordances; (H2) The Intent Token serves as a functional neural unit, computationally analogous to the biological neural assembly. TIWM offers a neuro-symbolic, cognition-first alternative to reconstruction-based planners, establishing a new direction: planning as active understanding, not passive reaction.

# Summary. An optional shortened abstract.
summary: "A paradigm shift from reconstructing the world to understanding it: planning through Belief-Intent Co-Evolution"

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
url_video: 'https://youtu.be/PqgWfie1Qo0'

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

{{< youtube Aeal4YLcb0I >}}

https://arxiv.org/abs/2511.05540v3

> 既自以心为形役，奚惆怅而独悲？
> 悟已往之不谏，知来者之可追。
> 实迷途其未远，觉今是而昨非。
——《归去来兮辞》陶渊明

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
