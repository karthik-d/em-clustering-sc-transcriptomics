# EM Clustering with Single-Cell Transcriptomic Data

Expectation-Maximization (EM) -based clustering algorithm to identify groups defined by biological variates as clusters in single-cell transcriptomic data.

## Quick links

- [Project summary report [PDF]](./docs/project-report.pdf).
- [Data subsets [CSVs]](./data).

## Clustering results with Poisson and Gaussian Priors

- **Data with only sex as biological variate** - neither captured by Poisson nor Gaussian.   
  <img src="./docs/assets/sex-variate-clustering-results.png" />

- **Data with sex and cell ontology as biological variates** - cell ontology captured by Gaussian prior.   
  <img src="./docs/assets/both-variate-clustering-results.png" />
