---
title: "Relational verification using reinforcement learning"
authors:
- Jia Chen
- admin
- Yu Feng
- Osbert Bastani
- Isil Dillig

date: "2019-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *OOPSLA 2019*
# publication_short: In [ICLR 2023](https://iclr.cc/Conferences/2023)

abstract: Relational verification aims to prove properties that relate a pair of programs or two different runs of the
same program. While relational properties (e.g., equivalence, non-interference) can be verified by reducing
them to standard safety, there are typically many possible reduction strategies, only some of which result
in successful automated verification. Motivated by this problem, we propose a new relational verification
algorithm that learns useful reduction strategies using reinforcement learning. Specifically, we show how
to formulate relational verification as a Markov decision process (MDP) and use reinforcement learning to
synthesize an optimal policy for the underlying MDP. The learned policy is then used to guide the search for
a successful verification strategy. We have implemented this approach in a tool called Coeus and evaluate
it on two benchmark suites. Our evaluation shows that Coeus solves significantly more problems within a
given time limit compared to multiple baselines, including two state-of-the-art relational verification tools.Relational verification aims to prove properties that relate a pair of programs or two different runs of the
same program. While relational properties (e.g., equivalence, non-interference) can be verified by reducing
them to standard safety, there are typically many possible reduction strategies, only some of which result
in successful automated verification. Motivated by this problem, we propose a new relational verification
algorithm that learns useful reduction strategies using reinforcement learning. Specifically, we show how
to formulate relational verification as a Markov decision process (MDP) and use reinforcement learning to
synthesize an optimal policy for the underlying MDP. The learned policy is then used to guide the search for
a successful verification strategy. We have implemented this approach in a tool called Coeus and evaluate
it on two benchmark suites. Our evaluation shows that Coeus solves significantly more problems within a
given time limit compared to multiple baselines, including two state-of-the-art relational verification tools.
# One sentence Summary.
summary: We propose a new relational verification algorithm that learns useful reduction strategies using reinforcement learning.

tags: 
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3360567
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
