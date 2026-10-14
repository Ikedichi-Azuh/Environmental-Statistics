# Environmental Statistics
## Lecture 4: Non-linear GLMs via Likelihood Optimisation
In the previous lectures, we used Generalised Linear Models (GLMs) to model different types of response variables.
The key idea was that a suitable probability distribution is combined with a linear predictor and a link function.

However, standard GLMs have an important structural restriction:

                    The linear predictor must be linear in the model parameters.

This lecture considers what we can do when the relationship between the predictors and the expected response is genuinely **non-linear in the parameters**.

Rather than treating such models as fundamentally different, we will look inside the GLM machinery and see that the essential task is still the same: define a probability model and estimate its parameters by optimising a likelihood.

### Learning Objectives
By the end of this lecture, you should be able to:
- Recognise when a standard GLM is insufficient because the model is non-linear in its parameters.
- Identify alternative distributions that may require specialised software implementations.
- Understand how transforming a response can sometimes make it compatible with an existing GLM implementation.
- Understand the general structure of a likelihood-based statistical model.
- Construct a likelihood for a non-linear model.
- Understand why the logarithm of the likelihood is usually used for numerical optimisation.
- Explain the roles of the *likelihood*, the *optimiser*, and the *Hessian*.
- Fit a non-linear model by directly optimising its likelihood.
- Recognise when standard non-linear least-squares methods such as `nls()` in R or `scipy.optimize.curve fit()` in Python are appropriate, and when a more general optimisation approach such as `optim()` in R or `scipy.optimize.minimize()` in Python is required.

---

## Material availability

**Materials not yet available.**

Materials will be released on **03 November 2026** from **08:45** (Berlin time).

