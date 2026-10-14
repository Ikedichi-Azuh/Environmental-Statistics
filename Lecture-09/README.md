# Environmental Statistics
## Lecture 9: Bootstrapping (and jackknife)
In environmental and biological statistics, we are often interested in estimating quantities such as means, regression coefficients, or more complex indices derived from data. However, in most real-world settings the true sampling distribution of these estimators is unknown or analytically intractable.

Classical approaches to uncertainty quantification rely on strong assumptions (e.g. normality, independence, or linear approximations via Taylor expansion). These assumptions are frequently violated in environmental data, especially in the presence of non-linearity, spatial dependence, or complex summary statistics.

This lecture introduces **resampling-based methods for uncertainty quantification**, focusing on bootstrapping as a practical and widely applicable alternative to analytical error propagation.

We also briefly introduce the jackknife as a related, simpler resampling technique.

In this lecture we cover:

-   The need for uncertainty quantification in statistical estimation
-   Classical error propagation and its limitations (Taylor approximation)
-   The bootstrap: idea, algorithm, and interpretation
-   Bootstrap-based standard errors and confidence intervals
-   Bootstrap applications: means, regression models, and complex indices
-   Limitations of the bootstrap  
-   The jackknife: leave-one-out resampling and variance estimation
-   Comparison of uncertainty estimates from OLS, jackknife, and bootstrap
-   Practical implementation in R using for-loops and simulation-based inference

---

## Material availability

**Materials not yet available.**

Materials will be released on **08 December 2026** from **08:45** (Berlin time).

