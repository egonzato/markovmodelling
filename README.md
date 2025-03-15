### Data

A survey was administered to participants coming from seven different countries. Questions were focused on demographics, medical characteristics and quality of life of each individual. This survey was sent out once a year for four years.

### Purpose

Explore univariate and joint trends, over the four time points of interest, in quality of life for the five domains. Latent Markov Models were used to explore presence of clusters of individuals that shared similar health problems.

### File

The following repository contains:

* Descriptive.Rmd: R markdown file that produces plots and tables to describe the population investigated. 

* Models.Rmd: R markdown file that performs statistical analysis for:

	* Cross-sectional latent class analysis, in each of the four time points, to evaluate heterogeneity of the latent class structure of the population.

	* Search for the optimal number of latent states, using grid search function. Metrics used: AIC, BIC and entropy.

	* Characterization of latent states based on the answers given for each of the five domains of the dependent variables.

	* Grid search of the optimal number of latent states in each of the strata of the categorical variables considered for adjustment.

	* Adjustment of the latent model for demographics and medical characteristics, to study how initial probabilities change with covariates.
