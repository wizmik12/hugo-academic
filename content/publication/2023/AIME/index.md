---
title: "Crowdsourcing Segmentation of Histopathological Images Using Annotations Provided by Medical Students"

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

date: "2023-06"
doi: "https://doi.org/10.1007/978-3-031-34344-5_29"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Artificial Intelligence in Medicine (AIME)*, edited by Springer, Portoroz (Slovenia), June 2023, pp. 245-249"
# publication_short: "*SR*"

abstract: "Segmentation of histopathological images is an essential task for cancer diagnosis and prognosis in computational pathology. Unfortunately, Machine Learning (ML) techniques need large labeled datasets to train accurate segmentation algorithms that generalize well. A possible solution to alleviate this burden is crowdsourcing, which distributes the effort of labeling among a group of (non-expert) individuals. The bias and noise from less experienced annotators may hamper the performance of machine learning techniques. So far, crowdsourcing approaches in ML leveraging these noisy labels achieve promising results in classification. However, crowdsourcing segmentation is still a challenge in histopathological images. This paper presents a novel crowdsourcing approach to the segmentation of Triple Negative Breast Cancer images. Our method is based on the UNet architecture incorporating a pre-trained ResNet-34 as a backbone. The noisy behavior of the annotators is modeled with a coupled network. Our methodology is validated on a real-world dataset annotated by medical students, where five classes are distinguished. The results show that our method with crowd labels achieves a high level of accuracy in segmentation (DICE: 0.7578), outperforming the well-known STAPLE (DICE: 0.7039) and close to the segmentation model using expert labels (DICE: 0.7723). In conclusion, the initial results of our work suggest that crowdsourcing is a feasible approach to segmentation in histopathological images https://github.com/wizmik12/CRowd_Seg."

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
url_code: 'https://github.com/wizmik12/CRowd_Seg'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_custom: [{name = "Paper", url = "https://link.springer.com/chapter/10.1007/978-3-031-34344-5_29"}]


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
