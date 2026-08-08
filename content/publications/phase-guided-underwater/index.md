---
title: 'Not All Pixels Sink: Phase-Guided Representation Learning For Underwater Image Restoration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Abhinav Rajput
  - admin
  - Sparsh Jain
  - Dinesh Kumar Vishwakarma

date: '2026-06-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *CVPR 2026 Workshop on New Trends in Image Restoration and Enhancement (NTIRE)*
publication_short: In *CVPR'26 Workshop (NTIRE)*

abstract: Underwater images are degraded by color absorption, scattering, and haze, resulting in low contrast, color distortion, and detail loss. This makes reliable restoration vital for marine research and autonomous navigation. To address this, we propose NemoNet, a novel phase-guided representation learning based encoder–decoder architecture. The architecture incorporates Spectral–Spatial Attention (SSA) block that couples Fourier phase-based pixel refinement with spatial attention to recover fine textures. These details are most severely degraded in underwater conditions and are critical for perceptually convincing restoration more broadly. Phase-based attention in skip connections ensures that they enhance useful representations instead of propagating artifacts. We introduce a hybrid Un/Supervised loss framework, where comprehensive supervised objectives are complemented by an unsupervised color constancy loss that mitigates wavelength-dependent color shifts in underwater scenes. We further introduce a no-reference Color-Plausibility Quality Index (CPQI) that augments Perceptual Index with a color consistency prior, which conventional metrics fail to capture. Comprehensive experiments demonstrate that the proposed approach outperforms existing state-of-the-art methods on supervised (UIEB, LSUI, EUVP) and unsupervised (U45) underwater image datasets across conventional and proposed metrics.

tags:
  - Computer Vision
  - Image Restoration
  - Representation Learning

# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: pdf
    url: https://openaccess.thecvf.com/content/CVPR2026W/NTIRE/papers/Rajput_Not_All_Pixels_Sink_Phase-Guided_Representation_Learning_For_Underwater_Image_CVPRW_2026_paper.pdf

slides: ''
---
