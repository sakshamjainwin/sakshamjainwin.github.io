---
title: 'IllumiCurveNet: Low-Light Image Enhancement of Lunar Permanently Shadowed Regions Using a Self-Guided Loss Framework'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sparsh Jain
  - Ashish Prajapati
  - Garvit Singh
  - Dinesh Kumar Vishwakarma
# Author notes (optional)

date: '2025-03-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conference on Neural Networks*
publication_short: In *IJCNN*

abstract: Lunar Permanently Shadowed Regions (PSRs) are areas near the Moon’s poles that remain in perpetual darkness due to its axial tilt. Obtaining clear and high-quality images of these regions are crucial for exploring lunar surface and detecting valuable minerals. However, due to the absence of illumination, PSR images often suffer from low visibility, poor contrast, and elevated noise levels, making their enhancement a significant challenge. To overcome these challenges, this paper introduces IllumiCurveNet, a novel framework leveraging an encoder-decoder architecture with spatial attention, dilated convolutions, and adaptive gamma correction for illuminance optimization. It uses the proposed Self-Guided Loss Framework that integrates the novel texture preservation and contrast enhancement losses, along with exposure control, spatial consistency, color consistency, and total variation losses, enabling robust enhancement without paired training data. IllumiCurveNet achieves state-of-the-art performance on PSR images with no-reference image quality metrics, surpassing other zero-shot methods. The results highlight IllumiCurveNet’s potential for applications in lunar mapping, rover navigation, and resource analysis, advancing visual perception in unlit extraterrestrial environments.


tags:
- Computer Vision
- Low-Light Image Enhancement
- Unsupervised Learning

# Display this page in the Featured widget?
featured: true

# # Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.5555/123456

# Custom links
links:
- type: pdf
  url: https://confcats-event-sessions.s3.amazonaws.com/ijcnn25/papers/2823.pdf
- type: code
  url: github.com/sakshamjainwin/IllumiCurveNet-IJCNN-2025

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '*Rome, Italy*'
  focal_point: ''
  preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
