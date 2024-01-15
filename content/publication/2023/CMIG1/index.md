---
title: "Are you sure it’s an artifact? Artifact detection and uncertainty quantification in histological images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Neel Kanwal
- admin
- Umay Kiraz
- Tahlita C.M. Zuiverloon
- Rafael Molina
- Kjersti Engan

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
# Date first published.

date: "2023-12"
doi: "https://doi.org/10.1016/j.compmedimag.2023.102321"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computerized Medical Imaging and Graphics*, March 2024, pp. 102321"
# publication_short: "*AIME*"

abstract: "Modern cancer diagnostics involves extracting tissue specimens from suspicious areas and conducting histotechnical procedures to prepare a digitized glass slide, called Whole Slide Image (WSI), for further examination. These procedures frequently introduce different types of artifacts in the obtained WSI, and histological artifacts might influence Computational Pathology (CPATH) systems further down to a diagnostic pipeline if not excluded or handled. Deep Convolutional Neural Networks (DCNNs) have achieved promising results for the detection of some WSI artifacts, however, they do not incorporate uncertainty in their predictions. This paper proposes an uncertainty-aware Deep Kernel Learning (DKL) model to detect blurry areas and folded tissues, two types of artifacts that can appear in WSIs. The proposed probabilistic model combines a CNN feature extractor and a sparse Gaussian Processes (GPs) classifier, which improves the performance of current state-of-the-art artifact detection DCNNs and provides uncertainty estimates. We achieved 0.996 and 0.938 F1 scores for blur and folded tissue detection on unseen data, respectively. In extensive experiments, we validated the DKL model on unseen data from external independent cohorts with different staining and tissue types, where it outperformed DCNNs. Interestingly, the DKL model is more confident in the correct predictions and less in the wrong ones. The proposed DKL model can be integrated into the preprocessing pipeline of CPATH systems to provide reliable predictions and possibly serve as a quality control tool."

# Summary. An optional shortened abstract.
summary: We propose crowdsourcing segmention for histopathological images. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_custom: [{name = "Paper", url = "https://www.sciencedirect.com/science/article/pii/S0895611123001398"}]


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
