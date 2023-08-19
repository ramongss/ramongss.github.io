---
title: "Decoding Electroencephalography Signal Response by Stacking Ensemble Learning and Adaptive Differential Evolution"
date: 2023-08-09
publishDate: 2023-08-19T18:40:00.0000Z
authors:
  [
    "Matheus Henrique Dal Molin Ribeiro",
    "Ramon Gomes da Silva",
    "José Henrique Kleinubing Larcher",
    "Andre Mendes",
    "Viviana Cocco Mariani",
    "Leandro dos Santos Coelho",
  ]
publication_types: ["2"]
abstract: "Electroencephalography (EEG) is an exam widely adopted to monitor cerebral activities regarding external stimuli, and its signals compose a nonlinear dynamical system. There are many difficulties associated with EEG analysis. For example, noise can originate from different disorders, such as muscle or physiological activity. There are also artifacts that are related to undesirable signals during EEG recordings, and finally, nonlinearities can occur due to brain activity and its relationship with different brain regions. All these characteristics make data modeling a difficult task. Therefore, using a combined approach can be the best solution to obtain an efficient model for identifying neural data and developing reliable predictions. This paper proposes a new hybrid framework combining stacked generalization (STACK) ensemble learning and a differential-evolution-based algorithm called Adaptive Differential Evolution with an Optional External Archive (JADE) to perform nonlinear system identification. In the proposed framework, five base learners, namely, eXtreme Gradient Boosting, a Gaussian Process, Least Absolute Shrinkage and Selection Operator, a Multilayer Perceptron Neural Network, and Support Vector Regression with a radial basis function kernel, are trained. The predictions from all these base learners compose STACK’s layer-0 and are adopted as inputs of the Cubist model, whose hyperparameters were obtained by JADE. The model was evaluated for decoding the electroencephalography signal response to wrist joint perturbations. The variance accounted for (VAF), root-mean-squared error (RMSE), and Friedman statistical test were used to validate the performance of the proposed model and compare its results with other methods in the literature, including the base learners. The JADE-STACK model outperforms the other models in terms of accuracy, being able to explain around, as an average of all participants, 94.50% and 67.50% (standard deviations of 1.53 and 7.44, respectively) of the data variability for one step ahead and three steps ahead, which makes it a suitable approach to dealing with nonlinear system identification. Also, the improvement over state-of-the-art methods ranges from 0.6% to 161% and 43.34% for one step ahead and three steps ahead, respectively. Therefore, the developed model can be viewed as an alternative and additional approach to well-established techniques for nonlinear system identification once it can achieve satisfactory results regarding the data variability explanation."
tags:
  [
    "Nonlinear system identification",
    "Machine learning",
    "Time-series modeling",
    "Differential evolution",
    "Electroencephalography signal response",
  ]
featured: True
publication: "*Sensors*"
doi: "10.3390/s23167049"
---
