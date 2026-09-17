# Environmental Statistics
## Lecture 11: Cross-validation vs AIC and Model Complexity
In environmental and ecological statistics, we are frequently confronted with models that are primarily used for **prediction rather than inference**. Examples include generalized additive models (GAMs), random forests, and other flexible regression approaches, where the model structure is often complex and only partially interpretable.

A central challenge in these settings is that increasing model flexibility almost always improves in-sample fit, but does not necessarily improve out-of-sample predictive performance. This creates the fundamental problem of **model evaluation and model selection under limited data availability**.

Two main frameworks are used to address this problem:
*  **Information criteria (such as AIC)**, which estimate expected predictive performance by correcting the optimism of the maximum likelihood fit through a complexity penalty.  
*  **Cross-validation**, which estimates predictive performance by repeatedly evaluating the model on held-out data.

Although these methods appear different, they address the same fundamental
statistical problem:
*  Training performance
*  future predictive performance

This difference is known as **optimism in training error**. 

AIC estimates this optimism analytically through a theoretical correction,
whereas cross-validation estimates it empirically by repeatedly separating
training and validation observations.

In this lecture, we examine how these ideas are applied in ecological data
analysis, with particular emphasis on prediction, model complexity, and
validation strategies for dependent environmental data.

In this lecture we cover:
*  The problem of model evaluation and model selection in ecological statistics
*  The difference between inference-focused and prediction-focused modelling
*  The bias–variance trade-off and its role in model complexity
*  Information criteria, with focus on AIC and its interpretation
*  Cross-validation as a direct estimator of predictive performance
*  Train-test splitting and its limitations
*  k-fold, repeated, and leave-one-out cross-validation
*  The relationship between AIC and cross-validation
*  Violations of independence assumptions in ecological data
*  Block cross-validation for spatial, temporal, and phylogenetic data
*  Using RMSE from cross-validation as an estimate of predictive performance
*  When to use bootstrap vs cross-validation
*  Practical implementation of cross-validation in R

---

## Material availability

**Materials not yet available.**

Materials will be released on **22 December 2026** from **08:45** (Berlin time).

