## GAMLSS modelling of tree taper

#### Problem definition

Tree taper models commonly used in the industry suffer from a variety of statistical issues: autocorrelation and multicollinearity. These problems are exacerbated in the cases of natural forests, where we have skewed and heteroskedastic data.
This code snippet is part of my research, done between 2024 - 2025, to develop a model that can account for these problems.As this is a code snippet, it does not cover all the things that were done. A research paper is expected to be published soon - ish.

#### Methodology

-   EDA
-   Model fitting - done via stepgAIC in the original research and simplified in this case
-   Evaluation on test dataset


As this is a snippet, the data was cut to about 10% of the original size, as I can't share the original dataset.
What is missing/ should be added later:
- Taper description of different trees
- Evaluation of predicted diameters, partial and total volumes

