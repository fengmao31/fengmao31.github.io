---
title: "Service Discovery-Based Hybrid Network Middleware for Efficient Communication in Distributed Robotic Systems"
authors:
- Shiyao Sang
date: "2023-10-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025."
publication_short: ""

abstract: |
  Robotic middleware is fundamental to ensuring reliable communication among system components and is crucial for intelligent robotics, autonomous vehicles, and smart manufacturing. However, existing robotic middleware often struggles to meet the diverse communication demands, optimize data transmission efficiency, and maintain scheduling determinism between Orin computing units in large-scale L4 autonomous vehicle deployments. This paper presents RIMAOS2C, a service discovery-based hybrid network communication middleware designed to tackle these challenges. By leveraging multi-level service discovery multicast, RIMAOS2C supports a wide variety of communication modes, including multiple cross-chip Ethernet protocols and PCIe communication capabilities. The core mechanism of the middleware, the Message Bridge, optimizes data flow forwarding and employs shared memory for centralized message distribution, reducing message redundancy and minimizing transmission delay uncertainty, thus improving both communication efficiency and scheduling stability. Tested and validated on L4 vehicles and Jetson Orin domain controllers, RIMAOS2C leverages TCP-based ZeroMQ to overcome the large-message transmission bottleneck inherent in native CyberRT middleware. In scenarios involving two cross-chip subscribers, RIMAOS2C eliminates message redundancy, enhancing transmission efficiency by 36%–40% for large data transfers while reducing callback time differences by 42%–906%. This research advances the communication capabilities of robotic operating systems and introduces a novel approach to optimizing communication in distributed computing architectures for autonomous driving systems.

# Summary. An optional shortened abstract.
summary: This research proposes an innovative robotic middleware framework designed to improve the diversity, efficiency, and stability of communication within distributed robotic operating systems.

tags:
- Robot

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
- robotaxi

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{< youtube uMvyOykTlkA >}}

This work is published in the 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) as an Oral Presentation.

https://arxiv.org/abs/2508.00947

https://ieeexplore.ieee.org/document/11246913

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
