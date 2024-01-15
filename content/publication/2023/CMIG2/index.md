---
title: "Learning from crowds for automated histopathological image segmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pablo Morales-Álvarez
- Lee A. D. Cooper
- Christopher Felicelli
- Jeffery Goldstein
- Brian Vadasz
- Rafael Molina
- Aggelos K. Katsaggelos

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
# Date first published.

date: "2024-03"
doi: "https://doi.org/10.1016/j.compmedimag.2024.102327"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computerized Medical Imaging and Graphics*, March 2024, pp. 102327"
# publication_short: "*AIME*"

abstract: "Automated semantic segmentation of histopathological images is an essential task in Computational Pathology (CPATH). The main limitation of Deep Learning (DL) to address this task is the scarcity of expert annotations. Crowdsourcing (CR) has emerged as a promising solution to reduce the individual (expert) annotation cost by distributing the labeling effort among a group of (non-expert) annotators. Extracting knowledge in this scenario is challenging, as it involves noisy annotations. Jointly learning the underlying (expert) segmentation and the annotators’ expertise is currently a commonly used approach. Unfortunately, this approach is frequently carried out by learning a different neural network for each annotator, which scales poorly when the number of annotators grows. For this reason, this strategy cannot be easily applied to real-world CPATH segmentation. This paper proposes a new family of methods for CR segmentation of histopathological images. Our approach consists of two coupled networks: a segmentation network (for learning the expert segmentation) and an annotator network (for learning the annotators’ expertise). We propose to estimate the annotators’ behavior with only one network that receives the annotator ID as input, achieving scalability on the number of annotators. Our family is composed of three different models for the annotator network. Within this family, we propose a novel modeling of the annotator network in the CR segmentation literature, which considers the global features of the image. We validate our methods on a real-world dataset of Triple Negative Breast Cancer images labeled by several medical students. Our new CR modeling achieves a Dice coefficient of 0.7827, outperforming the well-known STAPLE (0.7039) and being competitive with the supervised method with expert labels (0.7723)."

# Summary. An optional shortened abstract.
summary: We propose new method for histopathological image segmentation using multiple non-expert annotators. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/wizmik12/CRowd_Seg'
url_dataset: 'https://drive.google.com/drive/folders/17VukoKpwZclRrDcWSK1aYd_lPeqWNM8N?usp=sharing='
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_custom: [{name = "Paper", url = "https://www.sciencedirect.com/science/article/pii/S0895611124000041"}]


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
