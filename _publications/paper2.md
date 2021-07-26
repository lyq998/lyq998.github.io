---
title: "A Novel Training Protocol for Performance Predictors of Evolutionary Neural Architecture Search Algorithms"
collection: publications
permalink: /publication/paper2
excerpt: 'However, most ENAS algorithms require intensive computational resource, which is not necessarily available to the users interested.
Performance predictors are a type of regression models which can assist to accomplish the search, while without exerting much computational resource. 
Despite various performance predictors have been designed, they employ the same training protocol to build the regression models: 1) sampling a set of DNNs with performance as the training dataset, 2) training the model with the mean square error criterion, and 3) predicting the performance of DNNs newly generated during the ENAS. In this paper, we point out that the three steps constituting the training protocol are not well though-out through intuitive and illustrative
examples. Furthermore, we propose a new training protocol to address these issues, consisting of designing a pairwise ranking
indicator to construct the training target, proposing to use the logistic regression to fit the training samples, and developing a
differential method to building the training instances. To verify the effectiveness of the proposed training protocol, four widely
used regression models in the field of machine learning have been chosen to perform the comparisons on two benchmark datasets.
The experimental results of all the comparisons demonstrate that the proposed training protocol can significantly improve the performance prediction accuracy against the traditional training protocols.
'
date: 2021-01-27
venue: 'IEEE Transactions on Evolutionary Computation'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9336721/'
citation: 'Sun, Y., Sun, X., Fang, Y., Yen, G. G., & Liu, Y. (2021). A novel training protocol for performance predictors of evolutionary neural architecture search algorithms. IEEE Transactions on Evolutionary Computation, 25(3), 524-536.'
---
Evolutionary Neural Architecture Search (ENAS) can automatically design the architectures of Deep Neural Networks (DNNs) using evolutionary computation algorithms.
However, most ENAS algorithms require intensive computational resource, which is not necessarily available to the users interested.
Performance predictors are a type of regression models which can assist to accomplish the search, while without exerting much computational resource. 
Despite various performance predictors have been designed, they employ the same training protocol to build the regression models: 1) sampling a set of DNNs with performance as the training dataset, 2) training the model with the mean square error criterion, and 3) predicting the performance of DNNs newly generated during the ENAS. In this paper, we point out that the three steps constituting the training protocol are not well though-out through intuitive and illustrative
examples. Furthermore, we propose a new training protocol to address these issues, consisting of designing a pairwise ranking
indicator to construct the training target, proposing to use the logistic regression to fit the training samples, and developing a
differential method to building the training instances. To verify the effectiveness of the proposed training protocol, four widely
used regression models in the field of machine learning have been chosen to perform the comparisons on two benchmark datasets.
The experimental results of all the comparisons demonstrate that the proposed training protocol can significantly improve the performance prediction accuracy against the traditional training protocols.

[Download paper here](https://arxiv.org/pdf/2008.13187.pdf)

Recommended citation: Sun, Y., Sun, X., Fang, Y., Yen, G. G., & Liu, Y. (2021). A novel training protocol for performance predictors of evolutionary neural architecture search algorithms. IEEE Transactions on Evolutionary Computation, 25(3), 524-536.