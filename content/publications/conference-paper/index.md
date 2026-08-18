---
title: 'A Novel Trace Transfer Learning Framework to Improve Dataset Quality and Reduce Modeling Effort'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xu Han
  - me
  - Marcella Miller
  - Xiaodong Jia
  - James Moyne
  - Jimmy Iskandar
  - Fei Li
  - Arvind Shankar Raman

date: '2026-05-11'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "A Novel Trace Transfer Learning Framework to Improve Dataset Quality and Reduce Modeling Effort"

peer_reviewed: true
open_access: false

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
awards:
  - name: "Oral Presentation"
    level: selected

# Funders and grants. Required by many funders for compliance reporting.
funding:
  - funder: "Applied Materials"

abstract: Semiconductor manufacturing processes exhibit high variability in sensor traces across chambers, recipes, tools, hindering the deployment of robust fault detection (FD) models and limiting performance in data-scarce contexts. This study proposes a Dynamic Time Warping (DTW)-based trace transfer learning (TL) framework that unifies heterogeneous trace data to enable model reuse and reduce modeling effort. The method features (1) a trace transfer learning framework with trace distribution adjustment, (2) a context similarity metric to assess transfer suitability, and (3) a feature boundary segmentation mechanism for refined transfer paths. Validated on a public metal-etch dataset, the proposed approach reduces the false positive rate from 0.682 to 0.009 and improves the area under the curve (AUC) to 0.973. With the proposed TL framework, the number of FD models required across diverse data contexts can be significantly reduced, thereby lowering modeling and maintenance effort without compromising model performance.


tags:
  - Transfer Learning

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/ASMC69324.2026.11551245

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
