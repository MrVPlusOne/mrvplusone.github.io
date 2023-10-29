---
title: "Coeditor: Leveraging Contextual Changes for Multi-round Code Auto-editing"
authors:
- admin
- Greg Durrett
- Isil Dillig

date: "2023-05-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Developers often dedicate significant time to maintaining and refactoring existing code. However, most prior work on generative models for code focuses solely on creating new code, neglecting the unique requirements of editing existing code. In this work, we explore a multi-round code auto-editing setting, aiming to predict edits to a code region based on recent changes within the same codebase. Our model, Coeditor, is a fine-tuned CodeT5 model with enhancements specifically designed for code editing tasks. We encode code changes using a line diff format and employ static analysis to form large customized model contexts, ensuring appropriate information for prediction. We collect a code editing dataset from the commit histories of 1650 open-source Python projects for training and evaluation. In a simplified single-round, single-edit task, Coeditor significantly outperforms the best code completion approach -- nearly doubling its exact-match accuracy, despite using a much smaller model -- demonstrating the benefits of incorporating editing history for code completion. In a multi-round, multi-edit setting, we observe substantial gains by iteratively prompting the model with additional user edits. We open-source our code, data, and model weights to encourage future research and release a VSCode extension powered by our model for interactive usage.

# Summary. An optional shortened abstract.
summary: Coeditor, a code editing model trained on code commits, surpasses previous code completion methods and unveils a new multi-round auto-editing application.

tags: 
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2305.18584.pdf
url_code: 'https://github.com/MrVPlusOne/Coeditor'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
