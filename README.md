# 2020.Salmonella\_biofilm
Data sets and analyses for the paper ["Exposure of Salmonella biofilms to antibiotic concentrations rapidly
selects resistance with collateral tradeoffs"](https://doi.org/10.1038/s41522-020-00178-0).
See also [a write up on this work](https://quadram.ac.uk/new-insights-into-antibiotic-resistance-develops-biofilms/),
and the related manuscript ["Antibiotics select for novel pathways of resistance in biofilms"](https://doi.org/10.1101/605212).

## Phylogenetic analysis 
The trees were produced with notebook [plot\_trees.ipynb](plot_trees.ipynb).

## Regression for SNP visualisation
To decide which SNPs to plot as a heatmap, we used the
[glmnet](https://web.stanford.edu/~hastie/glmnet/glmnet_alpha.html) package to apply penalised regression.
This analysis is shown in the Jupyter notebook [tidy\_snps.ipynb](tidy_snps.ipynb).

