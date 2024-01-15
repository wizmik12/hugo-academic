---
title: "An end-to-end approach to combine attention feature extraction and Gaussian Process models for deep multiple instance learning in CT hemorrhage detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jose Pérez-Cano
- Yunan Wu
- Arne Schmidt
- admin
- Pablo Morales-Álvarez
- Rafael Molina
- Aggelos K. Katsaggelos

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
# Date first published.

date: "2023-11"
doi: "https://doi.org/10.1016/j.eswa.2023.122296"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Expert Systems with Applications*, April 2024, pp. 122296"
# publication_short: "*AIME*"

abstract: "Intracranial hemorrhage (ICH) is a serious life-threatening emergency caused by blood leakage inside the brain. Radiologists usually confirm the presence of ICH by analyzing computed tomography (CT) scans, so, developing an automated diagnosis system that can process this type of images has become an important research problem. One of the main challenges to apply AI algorithms in this setting is the lack of labeled data. To mitigate the labeling burden, Multiple Instance Learning (MIL) algorithms group instances into bags, relying solely on bag-level labels for model training. Due to their capacity to handle uncertainty and deliver accurate predictions, Gaussian Processes (GPs) stand out as promising classifiers for MIL problems. Recent research has also demonstrated the effectiveness of combining attention mechanisms with GPs for ICH detection. Nonetheless, existing methods have a notable limitation: they train the attention mechanism and the GP separately, resulting in suboptimal feature extraction for GP-based classification. In this study, we introduce an innovative end-to-end MIL model that concurrently trains the CNN backbone and attention mechanism along with the GP classifier. Our approach enhances the robustness and accuracy of bag predictions by optimizing feature extraction for GP-based classification. We validate our method experimentally by focusing on two ICH detection datasets. Our results reveal a significant performance advantage in terms of accuracy, F1-score, precision, and ROC-AUC score over existing MIL approaches, especially two-stage GP approaches. Additionally, we offer empirical insights into the functionality and effectiveness of our novel model."

# Summary. An optional shortened abstract.
summary: We propose an end2end method combining attention and Gaussian processes. We apply it to intracraneal hemorrhage detection. 

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
url_custom: [{name = "Paper", url = "https://www.sciencedirect.com/science/article/pii/S0957417423027987"}]


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
