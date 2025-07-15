---
title: "Cooperative ensemble learning model improves electric short-term load forecasting"
authors:
- Matheus Henrique Dal Molin Ribeiro
- admin
- Gabriel Trierweiler Ribeiro
- Viviana Cocco Mariani
- Leandro dos Santos Coelho

date: 2023-01-05
doi: "10.1016/j.chaos.2022.112982"

# Schedule page publish date (NOT publication's date).
# publishDate: "2023-01-04T12:06:53.292401Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Chaos, Solitons & Fractals*"
publication_short: ""

abstract: "Efficient models for short-term load forecasting (STLF) plays a crucial role in establishing the companies’ energetic planning due to their importance in electric power distribution and generation systems. An ensemble learning model based on dual decomposition approach, which combines two signals decomposition techniques, machine learning models and hyperparameters optimization based on metaheuristics, is applied to electric STLF. The seasonal and trend decomposition using locally-weighted regression (STL) decompose the time series into seasonal, trend, and residual components. Moreover, Variational Mode Decomposition (VMD) is applied to decompose the STL residual into different frequencies. Also, seasonal Naïve is adopted to handle the seasonal patterns. Moreover, due to the nonlinearities of the remaining components, an eXtreme gradient boosting model with hyperparameters tuned by a coyote optimization algorithm, extreme learning machines, ridge regression, and support vector regression models are employed to handle the STL trend and VMD components. The datasets from five regions and four seasons of the year for the Australian energy market operator are used to test the effectiveness of the proposed model for STLF with a multi-step-ahead horizon (12-hours-ahead and 24-hours-ahead). The performance analysis is based on the mean absolute error, symmetric mean absolute percentage error (sMAPE), overall weighted average, and Diebold–Mariano statistical test. The results of the study were divided into four comparative experiments: comparisons with (i) single decomposed models, (i) dual decomposed models, (iii) non-decomposed models, and (iv) state-of-art models. Regarding the sMAPE performance criterion, the proposed models achieved errors between 0.75%–3.18% and 1.56%–7.72% for STLF 12 and 24-hours-ahead. In the comparative scenarios, the proposed model improved the forecasting results up to 99% regarding compared models in terms of overall weighted average. Lastly, the proposed cooperative ensemble learning model outperformed 71.25% of the state-of-art models regarding forecasting error reduction in terms of sMAPE. From a broader perspective, the proposed cooperative ensemble learning model showed to be an efficient tool based of forecasting erros reduction for STLF due to its capability to improve forecasting accuracy and achieve reliable forecasting results compared with observed ones."

tags:
- Ensemble learning methods
- Machine learning
- Short-term load forecasting
- Seasonal and trend decomposition
- Variational mode decomposition

featured: false

# - name: ""
#   url: ""
# url_code: ''
# url_dataset: ''
# url_poster: ''
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
#projects: []

# Slides (optional).
# slides: ""
---
