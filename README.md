# PD1-WES
**"A Single Dose of Neoadjuvant PD-1 Blockade Predicts Clinical Outcomes in Resectable Melanoma"**

<br>

Scripts for somatic variant calling and allele-specific copy number profiling in matched tumor/normal whole exome sequencing data.

Required Software:

 * Python 3.6+
 * Snakemake
 * Samtools
 * GATK 4
 * R
 * Sequenza (R Package)
 * Sequenza-utils

## Usage
```
snakemake -s mutect2.snake --configfile config.yaml
snakemake -s sequenza.snake --configfile config.yaml
```

## Author
Brad Wubbenhorst
<bwubb@pennmedicine.upenn.edu>

## Paper Citation
Huang, A.C., Orlowski, R.J., Xu, X. et al. A single dose of neoadjuvant PD-1 blockade predicts clinical outcomes in resectable melanoma. Nat Med 25, 454–461 (2019). https://doi.org/10.1038/s41591-019-0357-y

[![DOI](https://zenodo.org/badge/162582612.svg)](https://zenodo.org/badge/latestdoi/162582612)
