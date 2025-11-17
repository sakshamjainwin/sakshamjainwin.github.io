---
title: "DECA-DiaXEL: An Explainable Ensemble Learning Framework for Early Diabetes Detection in ICU Settings"
authors:
- admin
- Atishay Jain
- Shashvat Singhal
- Dinesh Kumar Vishwakarma
author_notes:
- "Equal contribution"
- "Equal contribution"
# date: "2015-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Computing, Communication and Learning 2025*"
publication_short: "COCOLE"

abstract: Diabetes mellitus poses a serious risk among patients admitted to intensive care units, where early detection is critical to guiding timelyinterventionsandpreventingcomplications.Thisstudyintroduces DECA-DiaXEL, a robust and interpretable machine learning framework designed for the early prediction of diabetes onset using high-dimensional clinical data from the WiDS 2021 dataset. At the core of this framework lies the novel Dimensional Expansion–Contraction Architecture (DECA),which first expands the feature space through domain-informed engineering and subsequently contracts it using a hybrid feature selection strategy. The expansion phase generates over 4,000 features capturing physiological variability, comorbidity indicators, temporal dynamics, and group-level statistics. The contraction phase mitigates redundancy and overfitting through a layered selection approach combining variance thresholding, progressive correlation elimination, cumulative importance filtering, and LightGBM-based ranking. DECA-DiaXEL also incorporates LightGBM-based iterative imputation to handle missing values and logical consistency enforcement during preprocessing. The final ensemble model, trained through extensive hyperparameter tuning and evaluated using ROC-AUC, accuracy, and weighted F1-score, achieved a ROC-AUC of 0.8781 and a weighted F1-score of 0.84, surpassing existing state-of-the-artbenchmarks.ComprehensiveablationstudiesandSHAP-based interpretability analysis confirmed the robustness and clinical relevance of the proposed architecture.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

hugoblox:
  ids:
    arxiv: 1512.04133v1

# links:
#   - type: pdf
#     url: http://arxiv.org/pdf/1512.04133v1
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: ""
  # - type: video
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
slides: ""
---
