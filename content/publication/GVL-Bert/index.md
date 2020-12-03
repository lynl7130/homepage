---
title: "Semantically Relevant Scene Graphs for Visual Commonsense Reasoning (submitted to CVPR 2021)"
authors:[]
date: "2019-11-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "submitted to 2021 Conference on Computer Vision and Pattern Recognition"
publication_short: "submitted to CVPR 2021"

abstract: Answering complex questions about images is an ambitious goal for machine intelligence, which requires a joint understanding of images, text, and commonsense knowledge, as well as a strong reasoning ability. Recently, multi-modal transformers have made a great progress in the task of Visual Commonsense Reasoning (VCR), by jointly understanding visual objects and text tokens through layers of cross-modality attention. However, these approaches do not utilize the rich structure of the scene and the interactions between objects which are essential in answering complex commonsense questions. In this work, we propose a Graph Vision-Language BERT Model (GVL-BERT) that can exploit the graph structure of visual scene graphs, in order to enrich the visual information that is used by transformers. Moreover, we propose a novel method to train scene graph generation models using textual annotations in a weakly-supervised manner, in order to adapt scene graph models to downstream applications without annotation effort. Different from traditional scene graphs, our proposed model can capture visual concepts that are semantically more relevant to the VCR domain. We further devise a concept selection mechanism to prune generated scene graphs given an input question, to create more semantically relevant input which facilitates the reasoning process. Extensive experiments on the challenging task of VCR show significant performance boost compared with the state-of-the-art methods, and prove the efficacy of each proposed component.

# Summary. An optional shortened abstract.
# summary: Justified that explicitly utilizing scene priors in the form of semantic scene completion with self-calibrated confidence estimation and spatial action map could help object-goal navigation.

tags: []

featured: false

links: []

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ""
url_video: ''
url_source: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false
  placement: 1

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
slides: example
---


+++
