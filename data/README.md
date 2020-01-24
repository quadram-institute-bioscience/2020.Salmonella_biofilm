## description of files

### phylogenetic analysis
* **FILE.aln.log:** output log from IQ-TREE
* **FILE.aln.treefile:** maximum likelihood tree using IQ-TREE (and fixed `HKY+G` model)
* **FILE.png:** image of estimated tree, plotted with `ggtree` for R. 

### SNP regression analysis
* [all\_snps.persample](all_snps.persample) concatenation and processing of all `snps.csv` from snippy
* [all\_snps.uniq](all_snps.uniq) count statistics about SNPs from file above
