# The Allelic Fold Change (aFC) estimates for all independent cis-eQTLs across 49 tissues in GTEx v8 release.

The aFC-n model is the multi-variant generalization of the [aFC approach](https://github.com/secastel/aFC), to accurately estimate the cis-regulatory effect size in genes associated with multiple conditionally independent eQTLs. Notably, aFC-n is the first method that allows for predicting genetically regulated gene expression in a haplotype-specific fashion, paving the way for a future class of genome association studies that can systematically incorporate allele dosage effects.

This dataset is generated using [aFC-n software package](https://github.com/wickdChromosome/aFC-n), 10.5281/zenodo.8412460, to calculate effect sizes for ~half a million independent cis-eQTLs across 49 tissues in the GTEx v8 release as described in the manuscript.

### aFC_n_Oct2022 contains:

- **gene_id** : Ensembl gene ID
- **variant_id** : eQTL ID associated to the gene
- **log2_aFC** : The log2 of eQTL effect sizes measured as allelic Fold Change (aFC).
- **log2_aFC_min_95_interv** : Lower bound 95% confidence interval 
- **log2_aFC_plus_95_interv**: Upper bound 95% confidence interval



