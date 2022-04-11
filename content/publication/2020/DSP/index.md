---
title: "A TV-based image processing framework for blind color deconvolution and classification of histological images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors: ["Fernando Pérez-Bueno", admin, "Miguel Vega", "Javier Mateos", "Valery Naranjo", 
"Rafael Molina", "Aggelos K. Katsaggelos"]

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
# Date first published.

date: "2020-06"
doi: "https://doi.org/10.1016/j.dsp.2020.102727"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Digital Signal Processing*. Volume 101, no. 6, June 2020. "
publication_short: "*DSP*"

abstract: "In digital histopathological image analysis, two conflicting objectives are often pursued: closeness to the original tissue and high classification performance. The former objective tries to recover images (stains) that are as close as possible to the ones obtained by staining the tissue with a single dye. The latter objective requires images that allow the extraction of better features for an improved classification, even if their appearance is not close to single stained tissues. In this paper we propose a framework that achieves both objectives depending on the number of stains used to mathematically decompose the scanned image. The proposed framework uses a total variation prior for each stain together with the similarity to a given reference color-vector matrix. Variational inference and an evidence lower bound are utilized to automatically estimate all the latent variables and model parameters. The proposed methodology is tested on real images and compared to classical and state-of-the-art methods for histopathological blind image color deconvolution and prostate cancer classification."

# Summary. An optional shortened abstract.
summary: A new color normalization method for histopathological images. This bayesian method is based on Total Variation.

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
# custom_url: 'https://www.sciencedirect.com/science/article/pii/S0169260722001699'

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
