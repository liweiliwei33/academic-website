---
title: 'How Effective and Robust is Sentence-Level Data Augmentation for Named Entity Recognition?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Runmin Jiang
  - Xin Zhang
  - Jiyue Jiang
  - admin
  - Yuhao Wang

# Author notes (optional)
author_notes:
  - 'corresponding author'
    
date: '2022-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *NLPCC 2022*
publication_short: In *NLPCC 2022*

abstract: Data augmentation is a simple but effective way to improve the effectiveness and the robustness of pre-trained models. However, they are difficult to adapt to token-level tasks such as named entity recognition (NER) because of the different semantic granularity and more fine-grained labels. Inspired by some mixup augmentations in computer vision, we proposed three sentence-level data augmentations including CMix, CombiMix, TextMosaic, and adapted them to the NER task. Through empirical experiments on three authoritative datasets (OntoNotes4,CoNLL-03,OntoNotes5),we found that these methods will improve the effectiveness of the models if controlling the number of augmented samples. Strikingly, the results show our approaches can greatly improve the robustness of the pre-trained model even over strong baselines and token-level data augmentations. We achieved state-of-the-art (SOTA) in the robustness evaluation of the CCIR CUP 2021. The code is available at https://github.com/jrmjrm01/SenDA4NER-NLPCC2022.

# Summary. An optional shortened abstract.
summary: In this work, we propose three sentence-level data augmentations including CMix, CombiMix, TextMosaic, and adapted them to the NER task. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2204.05953.pdf'
url_code: 'https://github.com/jrmjrm01/SenDA4NER-NLPCC2022'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).