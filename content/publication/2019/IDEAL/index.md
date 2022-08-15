---
title: "Classifying Prostate Histological Images Using Deep Gaussian Processes on a New Optical Density Granulometry-Based Descriptor"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Adrián Colomer
- María A. Sales
- Valery Naranjo
- Rafael Molina

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-11"
doi: "https://doi.org/10.1007/978-3-030-33607-3_5"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Intelligent Data Engineering and Automated Learning 2019*
publication_short: In *IDEAL 2019*

abstract: The increasing use of whole slide digital scanners has led to an enormous interest in the application of machine learning techniques to detect prostate cancer using eosin and hematoxylin stained histopathological images. In this work the above problem is approached as follows: the optical density of each whole slide image is calculated and its eosin and hematoxylin concentration components estimated. Then, hand-crafted features, which are expected to capture the expertise of pathologists, are extracted from patches of these two concentration components. Finally, patches are classified using a Deep Gaussian Process on the extracted features. The new approach outperforms current state of the art shallow as well as deep classifiers like InceptionV3, Xception and VGG19 with an AUC value higher than 0.98.

# Summary. An optional shortened abstract.
summary: We introduce the use of a new optical density descriptor together with deep gaussian processes for cancer detection in histological prostate images. This combination outperforms the current state of the art in histopathology both shallow classifiers and deep neural networks like InceptionV3, Xception and VGG19 with an AUC value higher than 0.98.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: 'https://cvblab.synology.me/PublicDatabases/SICAPv1.zip'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects:
- SICAP

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
