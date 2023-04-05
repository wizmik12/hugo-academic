---
title: "Deep Gaussian Processes for classification with multiple noisy annotators. Application to breast cancer tissue classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pablo Morales-Álvarez
- Lee A. D. Cooper
- Rafael Molina
- Aggelos K. Katsaggelos

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
# Date first published.

date: "2023-01"
doi: "https://doi.org/10.1109/ACCESS.2023.3237990"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*, Volume 11, January 2023, pp. 6922 - 6934"
# publication_short: "*SR*"

abstract: "Machine learning (ML) methods often require large volumes of labeled data to achieve meaningful performance. The expertise necessary for labeling data in medical applications like pathology presents a significant challenge in developing clinical-grade tools. Crowdsourcing approaches address this challenge by collecting labels from multiple annotators with varying degrees of expertise. In recent years, multiple methods have been adapted to learn from noisy crowdsourced labels. Among them, Gaussian Processes (GPs) have achieved excellent performance due to their ability to model uncertainty. Deep Gaussian Processes (DGPs) address the limitations of GPs using multiple layers to enable the learning of more complex representations. In this work, we develop Deep Gaussian Processes for Crowdsourcing (DGPCR) to model the crowdsourcing problem with DGPs for the first time. DGPCR models the (unknown) underlying true labels, and the behavior of each annotator is modeled with a confusion matrix among classes. We use end-to-end variational inference to estimate both DGPCR parameters and annotator biases. Using annotations from 25 pathologists and medical trainees, we show that DGPCR is competitive or superior to Scalable Gaussian Processes for Crowdsourcing (SVGPCR) and other state-of-the-art deep-learning crowdsourcing methods for breast cancer classification. Also, we observe that DGPCR with noisy labels obtains better results ( F1=81.91 %) than GPs ( F1=81.57 %) and deep learning methods ( F1=80.88 %) with true labels curated by experts. Finally, we show an improved estimation of annotators’ behavior."

# Summary. An optional shortened abstract.
summary: We propose Deep Gaussian Processses for crowdsourcing. We apply them to tissue classification in digital pathology.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/wizmik12/DGPCR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_custom: [{name = "Paper", url = "https://ieeexplore.ieee.org/abstract/document/10019276"}]


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
