M-type smoothing-spline estimators for robust non-parametric regression. The estimators are described in detail in Kalogridis (2020).
They are implemented with the B-spline representation of natural splines (see, e.g., Hastie et al.(2009)) in combination with the penalized variant of IRWLS (Maronna 2011).
For the selection of the penalty parameter a mixed approach is adopted: preliminary grid search followed by numerical optimization.
The R-code reproduces the simulations experiment in the paper (up to a random seed) and the real-data examples there.
Contact me at ioannis.kalogridis@kuleuven.be for remarks or suggestions.
