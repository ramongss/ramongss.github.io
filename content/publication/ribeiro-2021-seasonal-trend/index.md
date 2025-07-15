---
title: "Seasonal-trend and multiobjective ensemble learning model for water consumption forecasting"
authors:
- Matheus Henrique Dal Molin Ribeiro
- admin
- José Henrique Kleinübing Larcher
- Viviana Cocco Mariani
- Leandro Santos Coelho

date: 2021-07-01
doi: "10.1109/ijcnn52387.2021.9534104"

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-03-02T23:25:02.877329Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Joint Conference on Neural Networks (IJCNN)*"
publication_short: ""

abstract: "Water consumption forecasting is essential for the development of efficient city planning. Due to the non-linearities and relations of the water consumption with different factors the development of an accurate forecasting system is challenging. This paper proposes a seasonal, trend, and multiobjective ensemble learning model to forecast multi-step-ahead (one, two, and three-month-ahead) water consumption for two cities of Paraná state in Brazil. The proposed data analysis uses seasonal and trend decomposition using Loess (STL) to split the original data into the seasonal, trend, and residual components. In the next stage, the machine learning models named Support Vector Regression and Ridge Regression as well as the stochastic approach Gaussian Processes model are employed to train and predict the STL components. The previous components are weighted integrated to compose a heterogeneous ensemble learning of components obtaining the final forecasts. The elitist Non-Dominated Sorting Genetic Algorithm-version II (NSGA-II) is adopted to obtain the weights assigned to the components. The best model has better generalization out-of-sample considering the root mean squared error, mean absolute error, and mean absolute percentage error criteria in respect to the minimization problem. Through developed comparisons, results showed that combining STL and multi-objective optimization with a heterogeneous ensemble learning can achieve high forecasting accuracy in comparison with some models. The framework proposed in this paper is effective to obtain reliable water consumption forecasting and can support and help future decisions."

tags:
- Decomposition
- Water consumption
- Ensemble learning
- Forecasting
- Multiobjective optimization

featured: false

# - name: ""
#   url: ""
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
url_slides: "/slides/2021_IJCNN_MATHEUS.pdf"
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
