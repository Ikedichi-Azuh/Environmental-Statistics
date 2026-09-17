# Environmental Statistics
## Lecture 13: Plotting and Variable Importance

Modern machine-learning models, particularly tree-based ensemble models such
as Random Forests and Gradient Boosting, can capture complex nonlinear
relationships and interactions between predictors. However, this flexibility
makes their predictions difficult to interpret because the relationship
between individual predictors and model predictions is often not directly
visible.

In traditional statistical models, predictor effects are often summarized using
estimated parameters. For example, in a linear regression model, regression
coefficients describe the expected change in the response associated with a
change in a predictor, under the assumptions of the fitted model.

However, complex models such as Random Forests, Gradient Boosting, and Neural
Networks do not provide simple coefficients. Their predictions are generated
through many nonlinear transformations and interactions between variables.

Therefore, an important question after fitting a predictive model is:

     How can we understand what the model has learned?

This lecture introduces methods from explainable machine learning (xAI) that
help visualize and quantify predictor effects.

The main objectives are:

*  understand why complex models require specialized interpretation tools;
*  visualize nonlinear relationships between predictors and predictions;
*  introduce Partial Dependence Plots (PDP), also known as marginal effect
plots, Individual Conditional Expectation (ICE) plot and Accumulated Local Effects (ALE) plot;
*  distinguish between conditional effects and marginal effects;
*  quantify predictor importance using model-specific and model-agnostic
approaches;
*  understand the role of uncertainty when interpreting machine-learning
models.

The goal is not only to build accurate models, but also to understand why these
models produce their predictions.
