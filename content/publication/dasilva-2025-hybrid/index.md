---
title: "Hybrid machine learning models applied to daily urban water consumption prediction"
authors:
- admin
- Luis Fernando Agottani
- Anderson Schamne
- Andre Silva
- Gustavo Rafael Collere Possetti
- Leandro Santos Coelho
- Viviana Cocco Mariani

date: "2025-06-30"
doi: "10.1109/IJCNN64981.2025.11227717"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-08-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2025 International Joint Conference on Neural Networks (IJCNN)*"
publication_short: ""

abstract: This study proposes hybrid machine learning (ML) models to predict the daily urban water consumption scenario in a neighborhood Brazilian city. The framework evaluates various signal decomposition modes, including empirical wavelet transform (EWT), complete ensemble empirical mode decomposition with adaptive noise (CEEMDAN), seasonal-trend decomposition (STL) using LOESS Locally Estimated Scatterplot Smoothing with locally estimated scatterplot smoothing, and variational mode decomposition (VMD), to prepare the dataset. The decomposed data are combined with different ML models such as Bayesian regularized neural networks (BRNN), extreme learning machines (ELM), k-nearest neighbor (KNN), multilayer perceptron neural network (MLP), support vector regression with linear kernel function (SVRL), and support vector regression with radial basis function kernel (SVRR) for daily short- and long-term forecasting. The CEEMDAN-SVRL and VMD-SVRL hybrid models are found to have the best results in terms of statistical metrics and performance criteria, significantly improving the prediction accuracy and the stability of the results. The study demonstrates the potential of ML frameworks to improve water resource planning and management by accurately predicting water consumption scenarios. Some results obtained suggested that the VMD-SVRL model performed better in most scenarios.

# Summary. An optional shortened abstract.
# summary:

tags:
- Empirical wavelet transformation
- Machine learning
- Time series forecasting
- Variational mode decomposition
- Water consumption

featured: true

# links:
# - name: ""
#   url: ""
# url_code: ''
# url_dataset: ''
url_poster: 'poster/2025_POSTER_IJCNN.pdf'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# image:
#   placement: 4
#   caption: ""
#   focal_point: "Smart"
#   preview_only: false
#   alt_text: 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
