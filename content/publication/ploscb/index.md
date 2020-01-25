---
title: "Deep convolutional models improve predictions of macaque V1 responses to natural images"
authors:
- Santiago A. Cadena
- Goerge H. Denfield
- Edgar Y. Walker
- Leon A. Gatys
- Andreas S. Tolias
- Matthias Bethge
- Alexander S. Ecker

date: "2019-04-23T00:00:00Z"
doi: "https://doi.org/10.1371/journal.pcbi.1006897"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *PLos Computational Biology 2019*
publication_short: In *PlosCB 2019*

abstract: 'Despite great efforts over several decades, our best models of primary visual cortex (V1) still predict spiking activity quite poorly when probed with natural stimuli, highlighting our limited understanding of the nonlinear computations in V1. Recently, two approaches based on deep learning have emerged for modeling these nonlinear computations: transfer learning from artificial neural networks trained on object recognition and data-driven convolutional neural network models trained end-to-end on large populations of neurons. Here, we test the ability of both approaches to predict spiking activity in response to natural images in V1 of awake monkeys. We found that the transfer learning approach performed similarly well to the data-driven approach and both outperformed classical linear-nonlinear and wavelet-based feature representations that build on existing theories of V1. Notably, transfer learning using a pre-trained feature space required substantially less experimental time to achieve the same performance. In conclusion, multi-layer convolutional neural networks (CNNs) set the new state of the art for predicting neural responses to natural images in primate V1 and deep features learned for object recognition are better explanations for V1 computation than all previous filter bank theories. This finding strengthens the necessity of V1 models that are multiple nonlinearities away from the image domain and it supports the idea of explaining early visual cortex based on high-level functional goals.'
# Summary. An optional shortened abstract.
summary: in PLos Computational Biology 2019

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006897
url_pdf: https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1006897&type=printable
url_code: 'https://github.com/sacadena/Cadena2019PlosCB'
url_dataset: 'https://gin.g-node.org/doi/Cadena_PlosCB19_data'
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
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

#{{% alert note %}}
#Click the *Slides* button above to demo Academic's Markdown slides feature.
#{{% /alert %}}

#Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
