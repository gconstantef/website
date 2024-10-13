---
title: "Learning to tune low-fidelity optimization models"
authors:
- Gonzalo Constante-Flores
- André Quisaguano
- Antonio J. Conejo
- Can Li
date: '2025-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']
# Publication name and optional abbreviated publication name.
publication: '*58th Hawaii International Conference on System Sciences (HICSS)*'
publication_short: ""

abstract: This paper presents a parametric quadratic approximation of the AC optimal power flow (AC-OPF) problem for time-sensitive and market-based applications. The parametric approximation preserves the physics-based but simple representation provided by the DC-OPF model and leverages market and physics information encoded in the data-driven demand-dependent parameters. To enable the deployment of the proposed model for real-time applications, we propose a supervised learning approach to predict near-optimal parameters, given a certain metric concerning the dispatch quantities and locational marginal prices (LMPs).  The training dataset is generated based on the solution of the accurate AC-OPF problem and a bilevel optimization problem, which calibrates parameters satisfying two market properties: cost recovery and revenue adequacy. We show the proposed approach's performance in various test systems in terms of cost and dispatch approximation errors, LMPs, market properties satisfaction, dispatch feasibility, and generalizability with respect to N-1 network topologies.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Low fidelity models, Machine learning, Optimization, Surrogate models

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: Learning to tune low-fidelity optimization models
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->