## Bayesian modelling of spatial tree mortality

#### Problem definition

Mortality, specially in natural forests, seems to follow some type of spatial pattern, which, in turn, requires the usage of specialized models to account for spatial autocorrelation

This notebook tries to use both pysal spreg module as well as a more flexible approach with pymc that adds a covariance component based off of the parcel index

#### Methodology

-   Chi-square test to check data distribution
-   Explore gdf with leafmap
-   Apply Moran I to identify possibility of spatial clustering
-   Applying models and evaluating performance

The final fitted pyMC model follows the following eq:

$$f \sim GP(0,n^2k_{Matern-5/2}(X,X';l))$$ $$\mu = \beta_0 + X_i\beta_i+f$$ $$\sigma \sim HalfNormal(1)$$
