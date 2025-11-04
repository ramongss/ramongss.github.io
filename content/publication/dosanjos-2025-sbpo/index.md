---
title: "Combination of Transformer-Based Models for Wind Data Forecasting"
authors:
- Doglas Querino dos Anjos
- Gilberto Reynoso-Meza
- admin

date: 2025-10-05
doi: "10.59254/sbpo-2025-212309"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-12-21T17:54:04.875379Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the LVII Brazilian Symposium on Operations Research*"
publication_short: ""

abstract: "This study explores the use of combined Transformer-based models for time seriesforecasting, evaluating the Informer, Autoformer, Transformer, and CALF architectures. Models were trained on wind data under two configurations, with and without denoising, and evaluated across different forecasting horizons. Two combination strategies were developed: a Multi-Objective Optimization (MOO) approach using NSGA-III to balance MAPE and RMSE, and another one through the SAW multicriteria technique, which dynamically selects the most suitable model at each time step based on sliding windows. Results show that the SAW model outperformed the MOO-based approach by adapting to the evolving behavior of the data, while the MOO model consistently provided stable performance compared to the based model. Moreover, denoising did not have a clear impact on accuracy but significantly reduced training time. It is concluded that combined approaches can offer more robust forecasts than individual models, especially in scenarios with pronounced temporal variability."

tags:
- Multi-objective Optimization
- Multicriteria Decision-making
- Time Series Forecasting

featured: false

# - name: ""
#   url: ""
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
url_slides: '/slides/2025_SBPO.pdf'
# url_pdf: ""
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
#projects: []

# Slides (optional).
# slides: ""
---
