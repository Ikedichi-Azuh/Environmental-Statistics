# Environmental Statistics
## Lecture 12: CART, RandomForest, Bagging and Boosting
In environmental and ecological statistics, we are often interested in
prediction rather than only inference. Many environmental relationships are
nonlinear and involve complex interactions between predictors, such as the
relationship between climate variables and species distributions, rainfall
patterns and flooding, or environmental gradients and ecosystem responses.

Flexible regression models can capture these complex patterns, but increased
flexibility also increases the risk of overfitting. A central challenge in
predictive modelling is therefore:

**How can we build flexible models that generalize well to new data ?**

Classification and Regression Trees (CART) provide a flexible approach by
dividing the predictor space into regions using recursive binary splits.
However, individual trees are often unstable and have high variance: small
changes in the data can result in substantially different predictions.

This motivates **ensemble methods**, where multiple trees are combined to
create stronger predictive models.

Two important ensemble approaches are:
*  **Bagging (bootstrap aggregation)**, where many models are fitted to
bootstrap samples and their predictions are averaged to reduce variance.

*  **Boosting**, where models are fitted sequentially, with each new model
aiming to improve the remaining prediction errors of the current ensemble.

Random Forests extend bagging by introducing additional randomness in the
selection of predictors at each tree split, while modern boosting methods such
as XGBoost provide powerful prediction approaches for structured environmental
datasets.

Although these methods often provide excellent predictive performance,
environmental modelling also requires careful evaluation of model reliability.
Important considerations include:

* predictive accuracy and generalization to new data;
* appropriate validation strategies;
* calibration of predicted probabilities for classification problems.

In this lecture, we introduce CART and tree-based ensemble methods, focusing
on their construction, the principles behind their improvement, and their
application to environmental prediction.

In this lecture we cover:

* Classification and Regression Trees (CART) and recursive splitting;
* Tree complexity, pruning, and cross-validation;
* Limitations of individual CART models;
* Bagging and bootstrap aggregation;
* Random Forests and random predictor selection;
* Weighted CART and its relationship to boosting;
* Boosting and Extreme Gradient Boosting (XGBoost);
* Calibration limitations of tree-based prediction models.

---

## Material availability

**Materials not yet available.**

Materials will be released on **12 January 2027** from **08:45** (Berlin time).

