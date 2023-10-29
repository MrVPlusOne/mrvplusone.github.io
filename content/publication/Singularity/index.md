---
title: "Singularity: Pattern Fuzzing for Worst Case Complexity"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jia Chen
  - Yu Feng
  - Kostas Ferles
  - Isil Dillig

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2018-03-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *FSE 2018*
# publication_short: In [ICLR 2020](https://iclr.cc/Conferences/2020)

abstract: "We describe a new blackbox complexity testing technique for determining the worst-case asymptotic complexity of a given application. The key idea is to look for an input pattern —rather than a concrete input— that maximizes the asymptotic resource usage of the program. Because input patterns can be described concisely as programs in a restricted language, our method transforms the complexity testing problem to optimal program synthesis. In particular, we express these input patterns using a new model of computation called Recurrent Computation Graph (RCG) and solve the optimal synthesis problem by developing a genetic programming algorithm that operates on RCGs. We have implemented the proposed ideas in a tool called Singularity and evaluate it on a diverse set of benchmarks. Our evaluation shows that Singularity can effectively discover the worst-case complexity of various algorithms and that it is more scalable compared to existing state-of-the-art techniques. Furthermore, our experiments also corroborate that Singularity can discover previously unknown performance bugs and availability vulnerabilities in real-world applications such as Google Guava and JGraphT."

# Summary. An optional shortened abstract.
summary: "A new blackbox complexity testing technique for determining the worst-case asymptotic complexity using program synthesis."

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://github.com/MrVPlusOne/Singularity/raw/develop/doc/PatternFuzzing.pdf"
url_code: "https://github.com/MrVPlusOne/Singularity"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
