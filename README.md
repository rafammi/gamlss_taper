## GAMLSS modelling of tree taper

#### Problem definition

Tree taper models commonly used in the industry suffer from a variety of statistical issues: autocorrelation and multicollinearity. These problems are exacerbated in the cases of natural forests, where we have skewed and heteroskedastic data.
This code snippet is part of my research, done between 2024 - 2025, to develop a model that can account for these problems.

#### Methodology

-   EDA
-   Model fitting
-   Evaluation on test dataset

As this is a snippet, the data was cut to about 10% of the original size, as I can't share the original dataset.

The resulting model used Box-Cox t distribution.W
