---
title: "SSCNav: Confidence-Aware Semantic Scene Completion for Visual Semantic Navigation (submitted to ICRA 2021)"
authors:
- Yiqing Liang
- Boyuan Chen
- Shuran Song
date: "2019-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication = "submitted to 2021 IEEE International Conference on Robotics and Automation"
publication_short = "submitted to ICRA 2021"

abstract: This paper focuses on visual semantic navigation, the task of producing actions for an active agent to navigate to a specified target object category in an unknown environment. To complete this task, the algorithm should simultaneously locate and navigate to an instance of the category. In comparison to the traditional point goal navigation, this task requires the agent to have a stronger contextual prior of indoor environments. We introduce SSCNav, an algorithm that explicitly models scene priors using a confidence-aware semantic scene completion module to complete the scene and guide the agent's navigation planning. Given a partial observation of the environment, SSCNav first infers a complete scene representation with semantic labels for the unobserved scene together with a confidence map associated with its own prediction. Then, a policy network infers the action from the scene completion result and confidence map. Our experiments demonstrate that the proposed scene completion module improves the efficiency of the downstream navigation policies.

# Summary. An optional shortened abstract.
summary: Justified that explicitly utilizing scene priors in the form of semantic scene completion with self-calibrated confidence estimation and spatial action map could help object-goal navigation.



featured: false


url_pdf: 
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project = "http://sscnav.cs.columbia.edu"
url_slides = ""
url_video = "https://www.youtube.com/watch?v=tfBbdGS72zg&feature=youtu.be"
url_source = ""

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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


image:
  placement = 1

