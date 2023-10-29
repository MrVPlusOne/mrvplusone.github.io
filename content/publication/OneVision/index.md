---
title: "OneVision: Centralized to Distributed Controller Synthesis with Delay Compensation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tongrui Li
  - Swarat Chaudhuri
  - Isil Dillig
  - Joydeep Biswas

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-04-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In "[IROS 2021](https://www.iros2021.org/)"
# publication_short: In [ICLR 2020](https://iclr.cc/Conferences/2020)

abstract: "We propose a new algorithm to simplify the controller development for distributed robotic systems subject to external observations, disturbances, and communication delays. Unlike prior approaches that propose specialized solutions to handling communication latency for specific robotic applications, our algorithm uses an arbitrary centralized controller as the specification and automatically generates distributed controllers with communication management and delay compensation. We formulate our goal as nonlinear optimal control -- using a regret minimizing objective that measures how much the distributed agents behave differently from the delay-free centralized response -- and solve for optimal actions w.r.t. local estimations of this objective using gradient-based optimization. We analyze our proposed algorithm's behavior under a linear time-invariant special case and prove that the closed-loop dynamics satisfy a form of input-to-state stability w.r.t. unexpected disturbances and observations. Our experimental results on both simulated and real-world robotic tasks demonstrate the practical usefulness of our approach and show significant improvement over several baseline approaches."

# Summary. An optional shortened abstract.
summary: "A controller synthesis framework that automatically handles delay compensation for distributed robotic systems using receding horizon control."

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2104.06588
url_code: https://github.com/MrVPlusOne/OneVision.jl
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/5YG32I6VI6E

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
