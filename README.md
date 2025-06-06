# Statistical-Power-Parametric-vs-Non-Parametric-Methods

## Project Overview

This project replicates and extends a published study comparing the effectiveness of parametric and non-parametric statistical tests when applied to non-normally distributed data. Using R, I simulated datasets and tested the statistical power of the t-test, Wilcoxon-Mann-Whitney (WMW) test, and Siegel-Tukey test under various conditions.

## Objectives

-Replicate Table 3 from Vickers (2005) using simulated data in R

-Compare statistical power of t-tests vs WMW across different sample sizes and correlations

-Introduce the Siegel-Tukey test and analyze its comparative power

## Key Results

-WMW outperformed t-tests at low sample sizes and low correlation values

-T-tests became more powerful with large sample sizes and high correlations

-Siegel-Tukey test was generally less powerful, confirming its limited usefulness in these contexts

## Tools & Techniques

-R (data simulation, loops, and hypothesis testing)

-Power calculation methods

-ggplot2 for heatmaps and data visualization

## Links
[Replication of Results project.pdf](Replication%20of%20Results%20project.pdf)
